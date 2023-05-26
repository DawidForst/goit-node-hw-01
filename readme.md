# Contacts Application

A simple command-line contacts application that allows users to manage their contacts.

## Features

- List all contacts
- Get a contact by ID
- Add a new contact
- Remove a contact by ID

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/) installed on your local machine.

### Installation

1. Clone the repository:

git clone https://github.com/yourusername/contacts-application.git

2. Change to the `contacts-application` directory:

cd contacts-application

3. Install the dependencies:

npm install

## Usage

After installation, you can perform different actions using command-line arguments:

### List all contacts
node index.js --action=list

### Get a contact by ID
node index.js --action=get --id=AeHIrLTr6JkxGE6SN-0Rw

### Add a new contact
node index.js --action=add --name="Jan Kowalski" --email="jan.kowalski@example.com" --phone="(123) 456-7890"

### Remove a contact by ID
node index.js --action=remove --id=AeHIrLTr6JkxGE6SN-0Rw
