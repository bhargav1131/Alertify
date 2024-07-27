# Alertify - A CLI Reminder Tool

A simple command-line reminder tool written in Go that allows you to set reminders at specified times. The tool will display a notification with your message when the reminder time is reached.

## Features

- Set reminders using the command line.
- Display a notification with the reminder message.
- Simple and easy to use.

## Prerequisites

- [Go](https://golang.org/doc/install) 1.22.5 or later
- [Beeep](https://github.com/gen2brain/beeep) library for notifications
- [When](https://github.com/olebedev/when) library for parsing time

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/bhargav1131/Alertify.git
    ```

2. Change to the project directory:

    ```bash
    cd Alertify
    ```

3. Download the dependencies:

    ```bash
    go get -u github.com/gen2brain/beeep
    go get -u github.com/olebedev/when
    ```

4. Build the project:

    ```bash
    go build
    ```

## Usage

Run the command with the desired time and message:
Example
```bash
go run main.go 10:32 Get Hydrated!
```

