Project Overview

Background and Motivation

The concept of social networks has evolved significantly, but they continue to face challenges such as the spread of misinformation, hate speech, and the lack of quality control. This project aims to tackle these challenges by integrating a "fame profile" system into a social network. Inspired by the novel Fameland by Tom J. Petersson, the fame profile tracks users' skills and expertise, assigning them positive or negative fame based on their contributions. This approach is envisioned as a way to ensure that knowledgeable voices are amplified while misinformation is minimized.

General Idea: Fame Profiles

In this project, we aim to create a social network where every user's contributions are filtered and judged based on their "fame profile." The fame profile is a record of a user's skills and expertise, which evolves based on their actions on the platform. The more expertise a user demonstrates in a particular area, the more their fame increases. Conversely, spreading misinformation or making unsubstantiated claims will negatively impact their fame.
Prerequisites

Python 3.8+
Django 3.2+
PostgreSQL or any other preferred RDBMS
Pip (Python package manager)

Tasks Implemented

API Enhancements:

Prevent publishing of posts in areas where the user's fame is negative.
Automatically adjust fame based on the truthfulness of posts.
Implement endpoints to retrieve experts and bullshitters in specific areas.
Additional Views:

HTML views for listing experts and bullshitters.
Follow and unfollow users directly from the timeline.
Extensions:

Creative ideas to further enhance the fame profile concept (details in extensions.txt).

License

This project is licensed under the MIT License - see the LICENSE file for details.

