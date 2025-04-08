# Leaderboard-Data Repository

Welcome to the Leaderboard-Data Repository! This repository is a central hub for tracking contributors' activity across various platforms, including GitHub and Slack.

## Introduction

In any collaborative project or community, recognizing and appreciating contributors' efforts is essential for fostering a vibrant and inclusive environment. The Leaderboard Repository aims to streamline this process by aggregating data from GitHub and Slack to acknowledge the valuable contributions made by individuals within our community.

By consolidating information about contributions, such as code commits, issue discussions, and Slack interactions, into a single location, the Leaderboard-Data Repository provides a transparent overview of the community's collective efforts. This not only celebrates individual achievements but also encourages collaboration and healthy competition, driving the community towards shared goals and objectives.


## Features

- **Contributors Data**: The `contributors.json` file contains detailed information about contributors, including their GitHub usernames, Slack usernames, and contribution statistics.

- **Configuration Files**: Customize the appearance of the leaderboard using the `config` directory, which includes images and a theme CSS file.
- **Custom CSS Theme**:Easily change the look and feel of the leaderboard.For Example,the [Modern Dark Theme](https://github.com/SatyaPriya-Sarika26/leaderboard-data/blob/main/config/theme.css)offers a stylish and accessible UI.
- **Enhance Visual Experience**:Smooth transition,hover effects,and a modern layout make the leaderboard visually appealing while maintaining readability.
config/theme-dark.css
  body {
background-color: #121212;
color:#f1f1f1;
font-family: 'segoe UI',sans-serif;
}
a {
color:bb86fc;
}
a:hover {
color:#ffffff;
}
.card {
background-color: #1e1e1e;
border: 1px solid #333;
box-shadow:0 2px 5px rgba(0,0,0.4);
padding:1rem;
border-radius:12px;
}
.header,footer {
background-color: #1f1f1f;
color:#fff;
padding:0.5rem 1rem;
border-radius:8px;
}
.button:hover {
background-color: #373737;
}


For detailed instructions on accessing and utilizing the leaderboard data, please refer to the [Leaderboard Repository](https://github.com/ohcnetwork/leaderboard) itself.

Additionally, you can find a template repository for organizing organizational data at [Leaderboard Org Data Template Repository](https://github.com/ohcnetwork/leaderboard-org-data-template/).
