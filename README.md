# WEB103 Project 1 - Hollow Knight Bosses Listicle

Submitted by: **Noor**

About this web app: **A list-based web app that displays Hollow Knight bosses in a card grid. Users can click any boss to view a detailed page with all boss fields.**

Time spent: **5** hours

## Required Features

The following **required** functionality is completed:

- [x] **The web app uses only HTML, CSS, and JavaScript without a frontend framework**
- [x] **The web app displays a title**
- [x] **The web app displays at least five unique list items, each with at least three displayed attributes (such as title, text, and image)**
- [x] **The user can click on each item in the list to see a detailed view of it, including all database fields**
- [x] **Each detail view should be a unique endpoint, such as as `localhost:3000/bosses/crystalguardian` and `localhost:3000/mantislords`**
- [x] *Note: When showing this feature in the video walkthrough, please show the unique URL for each detailed view. We will not be able to give points if we cannot see the implementation* 
- [x] **The web app serves an appropriate 404 page when no matching route is defined**
- [x] **The web app is styled using Picocss**

The following **optional** features are implemented:

- [x] The web app displays items in a unique format, such as cards rather than lists or animated list items

The following **additional** features are implemented:

- [x] Responsive grid layout for cards (auto-fit columns)

## Video Walkthrough

Here's a walkthrough of implemented required features:

![Video Walkthrough](https://github.com/user-attachments/assets/0a109cf5-d58d-4315-a7d5-39eddf69a0d4)

<!-- Replace this with whatever GIF tool you used! -->
GIF created with ...  ezgif.com
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

One challenge was ensuring each boss had a unique detail endpoint and that unknown routes correctly render a 404 page. After setting up Express routes and the frontend fetch calls, the list and detail views worked smoothly.

## License

Copyright **2026 Noor**

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

> http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
