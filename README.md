# Project 3 - *Parstagram*

**Parstagram** is a photo sharing app similar to Instagram but using Parse as its backend.

## Topics Demonstrated
### State Isolation & Interface Architecture
* **view-state-isolation** — Swapped views via Fragments to prevent cross-contamination of memory or UI thread leaks between active screens.
* **modular-ui-design** — Designed independent view containers (Feed, Compose, Profile) managed by a unified navigation controller.
* **state-machine-navigation** — Enforced deterministic UI state paths based on direct interaction with a BottomNavigationView controller.
* **client-side-routing** — Programmatically coordinated local intent contexts and fragment transactions within an operating system wrapper.

### Data Lifecycle & Pipeline Governance
* **data-handling-constraints** — Explicitly engineered the client-side logic to strictly cap and bound remote query payloads to exactly 20 elements.
* **payload-optimization** — Mitigated local device thread starvation and network overhead by hard-limiting relational database fetching rows.
* **backend-as-a-service-integration** — Structured communication lines natively to synchronize local application models with an abstract Parse cloud store.
* **asynchronous-network-io** — Dispatched asset fetching processes to background system threads to eliminate main UI frame drops.

### Information Architecture & Object Mapping
* **object-relational-mapping** — Translated local object attributes seamlessly into remote relational tables hosted on Back4App.
* **ephemeral-data-handling** — Managed volatile device memory footprints when loading and indexing binary objects (images) in local UI caches.
* **data-pagination-logic** — Segmented, limited, and indexed data stream arrays cleanly as a fundamental computing baseline.
* **information-architecture** — Categorized and structured relational photo objects to correlate with a singular user identity context.

### Software Engineering & Governance Constraints
* **rapid-prototyping** — Designed, deployed, tested, and confirmed a functional distributed mobile application under tight 5-hour time boundaries.
* **resource-constrained-development** — Engineered systems logic under intentional development time limits without abandoning functional completeness.
* **software-integration** — Programmatically aligned native Android layout resources, camera device APIs, and specialized Parse database SDKs.
* **systems-validation** — Tested a finished multi-view client layout to ensure UI elements updated cleanly following data mutations.

### Device & Computing Foundations
* **hardware-api-orchestration** — Navigated and called native Android device subsystem components to capture external media assets (Camera).
* **mobile-architecture** — Managed activity contexts, layout lifecycle bounds, and component relationships inside a mobile OS environment.
* **object-oriented-programming** — Used class inheritance structures and modular polymorphism to build out view elements.
* **decoupled-architecture** — Separated client presentation fragments entirely from data hosting layers (Back4App), protecting local operations from remote state changes.

## User Stories

The following **required** functionality is completed:

- [X] User can view the last 20 posts submitted to "Instagram".
- [X] The user should switch between different tabs - viewing all posts (feed view), compose (capture photos form camera) and profile tabs (posts made) using fragments and a Bottom Navigation View. (2 points)
- [ ] User can pull to refresh the last 20 posts submitted to "Instagram".

The following **optional** features are implemented:

- [ ] User sees app icon in home screen and styled bottom navigation view
- [ ] Style the feed to look like the real Instagram feed.
- [ ] User can load more posts once he or she reaches the bottom of the feed using infinite scrolling.
- [ ] Show the username and creation time for each post.
- [ ] User can tap a post to view post details, including timestamp and caption.
- [ ] User Profiles
      - [ ] Allow the logged in user to add a profile photo
      - [ ] Display the profile photo with each post
      - [ ] Tapping on a post's username or profile photo goes to that user's profile page and shows a grid view of the user's posts 
- [ ] User can comment on a post and see all comments for each post in the post details screen.
- [ ] User can like a post and see number of likes for each post in the post details screen.

The following **additional** features are implemented:

- [ ] User can view posts that they have posted in a timeline format

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/Angelica-M/Parstagram/blob/master/ParstagramDemo1.gif' width='250dp' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

No significant challenges were encountered.

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2021] [Angelica Magnussen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.



# Project 3 - *Parstagram*

**Parstagram** is a photo sharing app similar to Instagram but using Parse as its backend.

Time spent: **6** hours spent in total

## User Stories

The following **required** functionality is completed:

- [X] User can sign up to create a new account using Parse authentication.
- [X] User can log in and log out of his or her account.
- [X] The current signed in user is persisted across app restarts.
- [X] User can take a photo, add a caption, and post it to "Instagram".

The following **optional** features are implemented:

- [ ] User sees app icon in home screen and styled bottom navigation view
- [ ] Style the feed to look like the real Instagram feed.
- [ ] After the user submits a new post, show an indeterminate progress bar while the post is being uploaded to Parse.

The following **additional** features are implemented:

- [ ] User can view how many posts they have posted with the app

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/Angelica-M/Parstagram/blob/master/ParstagramDemo0.gif' width='250dp' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

No challenges were faced.

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2021] [Angelica Magnussen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
