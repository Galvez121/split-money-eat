# Friends and Bills Manager

A simple React application for managing friends and splitting bills among them.

## Overview

The Friends and Bills Manager is a React application designed to help you keep track of your friends and split bills with them. It allows you to add new friends, view their balances, and easily split bills, ensuring a fair and transparent way to manage shared expenses.

### Features

- **Add and Remove Friends:** Easily manage your list of friends.
- **View Friend Details:** Check details such as name, image, and balance for each friend.
- **Split Bills:** Conveniently split bills with selected friends.

## Function Explanation

### `handleShowAddFriend()`

Toggles the visibility of the "Add Friend" form.

### `handleAddFriend(friend)`

Adds a new friend to the list and hides the "Add Friend" form.

### `handleSelectedFriend(friend)`

Selects or deselects a friend, displaying their details or closing the selection.

### `handleSplitBill(value)`

Splits a bill with the selected friend, updating their balance accordingly.

### `FriendsList`

A functional component that renders a list of friends.

### `Friend`

A functional component that displays details for an individual friend, including their name, image, and balance.

### `AddFriendForm`

A form component for adding new friends, collecting name and image details.

### `FormBillSplit`

A form component for splitting bills with a selected friend, allowing the user to specify the bill amount, their own expense, and the friend's expense.
### Credits:

Credits to the creator of the React Course
-User [jonasschmedtmann](https://www.udemy.com/user/jonasschmedtmann/)
