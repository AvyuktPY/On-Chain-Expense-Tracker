# On-Chain-Expense-Tracker
Editing based on the task


Solidity Task
2 Check if a user is registered
Returns true or false based on whether a user has registered.
function isRegistered(address _addr) public view returns (bool) {
    return people[_addr].walletAddress != address(0);
    }


JavaScript Task
3 Show last expense label
Fetches and shows the description of the most recent expense
added.

{expenses.length > 0 && <p>Last Expense: {expenses[expenses.length - 1].label}</p>}
