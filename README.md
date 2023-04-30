# CoWApp - Collaborative Workspace App

<div align="center">

[![Build](https://img.shields.io/badge/Build-not_yet-red)](https://github.com/belboukayyoub/CoWApp/releases)
[![Version](https://img.shields.io/badge/version-v0.0.0-blue)](https://github.com/belboukayyoub/CoWApp/releases)
[![MIT](https://img.shields.io/badge/license-MIT-green)](https://opensource.org/licenses/MIT)

</div>

## About CoWApp

CoWApp it's a collaborative platform designed to facilitate teamwork by providing a range of tools for communication, task management, and project organization. It allows users to create teams, invite members, and collaborate effectively in a workspace that includes whiteboarding, chatting, conferencing, posting, scheduling, and more. The application also includes a reporting system for addressing issues and a leader concept to facilitate decision-making and ensure team productivity.

## Features

* **Create a team**: Users can create a team and invite team members to join.
* **Whiteboarding**: Users can use the app's whiteboarding feature to collaborate on ideas and projects.
* **Communication**: The app includes chat and conferencing tools to facilitate communication between team members.
* **Calendar**: The app includes a calendar with Kanban functionality to help teams manage their projects and deadlines.
* **Meetings planning**: The app includes a meetings planning feature.
* **Reclamation services**: Users can report people, bugs, and feedback to the app's administrators.
* **Leader concept**: The app includes a leadership concept with different leadership options, including manual vote, system vote, or fixed leadership.
* **Rules**:
  * **Team rules**: Users can agree on team rules, and any violations can be reported to the leader or app administrator.
  * **Global rules**: Users must adhere to global rules, and violations may result in a ban.

## Getting Started

To get started with the app, follow these steps:

* Clone this repository to your local machine.

* ```bash
  composer install
  ```

* ```bash
  cp .env.example .env
  ```

* ```bash
  php artisan key:generate
  ```

* ```bash
  php artisan serve 
  ```

* Open the api in your web browser by navigating to  <http://127.0.0.1:8000>

Note that this repo contain only API for this app checkout [the front-end](https://github.com/belboukayyoub/CoWApp-frontend) for this app.

## Contributing

We welcome contributions from anyone who wants to improve this app! To contribute, please follow these steps:

1. Fork this repository to your GitHub account.
2. Create a new branch for your changes.
3. Make your changes and commit them to your branch.
4. Push your changes to your fork.
5. Submit a pull request from your fork's branch to the main branch of this repository.

Please checkout [our Contributing guidelines](/docs/CONTRIBUTING.md)

## Issues and Bug Reports

If you find any issues or bugs with the app, please report them to us by opening a new issue in this repository.

## Contact Us

If you have any questions or feedback about the app, please contact us at [belboukayyoub@gmail.com](mailto:belboukayyoub@gmail.com). We'd love to hear from you!

## License

This app is licensed under the [MIT license](https://opensource.org/licenses/MIT).
