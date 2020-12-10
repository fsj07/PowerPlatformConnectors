# SwiftKanban Connector
This connector provides a set of actions releated to SwiftKanban by helping users manage their work effectively by leveraging the Kanban Methodology. Using this connector, you can add/modify cards. For example, create a SwiftKanban card, view board team members. You can create a comment on a specific card or discard abort the card.

## Pre-requisites
You will need the following to proceed:
* A Microsoft Power Apps or Power Automate plan with custom connector feature.
* A valid account. generated when purchasing a product at https://www.digite.com/swiftkanban/
* Generate an API key in the account provided at the time of purchase.

## Supported Operations
The connector supports the following operations:
* `GetCard`: Get card by Card ID
* `GetBoards`: Get all accessible boards
* `GetTeamMembers`: Get Team Members details in a board
* `AddComment`: Add comment to a card
* `GetCardTypes`: Get all the card types available in a board
* `AddCard`: Create a card
* `UpdateCard`: Update a Card
* `ArchiveCard`: Archive a card
* `DiscardAbortCard`: Discard or Abort a card
* `GetLaneAndQueue`: Get details of queues and sub-queues
* `MoveCardToBacklog`: Move a card to backlog