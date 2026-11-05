# Open-source contributions

A documented log of my contributions to external open-source projects, libraries, and developer tools. Each entry links directly to the upstream pull request, issue thread, and code diff on the original repository.

---

## Overview

| Metric | Count | Verified Repositories |
|---|---|---|
| **Merged Pull Requests** | **4** | [openvinotoolkit/model_server](https://github.com/openvinotoolkit/model_server), [AOSSIE-Org/Rein](https://github.com/AOSSIE-Org/Rein), [AOSSIE-Org/BabyNest](https://github.com/AOSSIE-Org/BabyNest), [GreedyBear-Project/GreedyBear](https://github.com/GreedyBear-Project/GreedyBear) |
| **Open Pull Requests** | **5** | [openvinotoolkit/model_server](https://github.com/openvinotoolkit/model_server), [AOSSIE-Org/Rein](https://github.com/AOSSIE-Org/Rein), [AOSSIE-Org/BabyNest](https://github.com/AOSSIE-Org/BabyNest), [fossasia/voxbento](https://github.com/fossasia/voxbento), [fossasia/scrum_helper](https://github.com/fossasia/scrum_helper) |
| **Superseded Pull Requests** | **1** | [GreedyBear-Project/GreedyBear](https://github.com/GreedyBear-Project/GreedyBear) (re-submitted as #1795 with clean branch) |
| **Documented Issues Authored** | **14** | 10 in core open-source organizations (6 open, 4 resolved via merged PRs) + 4 in community event tools |
| **Primary Stacks** | — | C++ (C++17/20), TypeScript, JavaScript, React, React Native, Node.js, WebRTC, Python (FastAPI) |

---

## Contributions index

### Pull Requests (10 Total: 4 Merged, 5 Open, 1 Superseded)

| Project | Pull Request | Stack / Area | Status |
|---|---|---|---|
| [openvinotoolkit/model_server](https://github.com/openvinotoolkit/model_server) | [PR #4694](https://github.com/openvinotoolkit/model_server/pull/4694): Reject whitespace-prefixed negative values in `stou64` | C++, String Parsing, GTest | **Merged** |
| [AOSSIE-Org/Rein](https://github.com/AOSSIE-Org/Rein) | [PR #442](https://github.com/AOSSIE-Org/Rein/pull/442): Replace `react-icons` with `lucide-react` to resolve build failure | TypeScript, React, Rolldown | **Merged** |
| [GreedyBear-Project/GreedyBear](https://github.com/GreedyBear-Project/GreedyBear) | [PR #1795](https://github.com/GreedyBear-Project/GreedyBear/pull/1795): Add accessible name and modern scroll listener to `ScrollToTopButton` | React, Accessibility (WCAG), Jest | **Merged** |
| [AOSSIE-Org/BabyNest](https://github.com/AOSSIE-Org/BabyNest) | [PR #285](https://github.com/AOSSIE-Org/BabyNest/pull/285): Include `user_id` in AI appointment updates payload | React Native, AsyncStorage | **Merged** |
| [openvinotoolkit/model_server](https://github.com/openvinotoolkit/model_server) | [PR #4726](https://github.com/openvinotoolkit/model_server/pull/4726): Reject malformed MediaPipe `servable_version` inputs | C++, MediaPipe Calculator, GTest | **Open** (Review pending) |
| [AOSSIE-Org/Rein](https://github.com/AOSSIE-Org/Rein) | [PR #455](https://github.com/AOSSIE-Org/Rein/pull/455): Detach stale `RTCDataChannel` event listeners on reconnect | TypeScript, WebRTC, Vitest | **Open** (Review pending) |
| [AOSSIE-Org/BabyNest](https://github.com/AOSSIE-Org/BabyNest) | [PR #304](https://github.com/AOSSIE-Org/BabyNest/pull/304): Add optional chaining for null `userContext` and import `addMedicine` in `RAGService` | React Native, Null Safety, Jest | **Open** (Review pending) |
| [fossasia/scrum_helper](https://github.com/fossasia/scrum_helper) | [PR #948](https://github.com/fossasia/scrum_helper/pull/948): Preserve custom date ranges in generated report headings | JavaScript, Date/Timezone Handling, Automated Testing | **Open** (Review pending) |
| [fossasia/voxbento](https://github.com/fossasia/voxbento) | [PR #999](https://github.com/fossasia/voxbento/pull/999): Return 400 Bad Request on invalid `language_code` in booth endpoints | Python, FastAPI, API Validation | **Open** (Merge conflict on `dev`) |
| [GreedyBear-Project/GreedyBear](https://github.com/GreedyBear-Project/GreedyBear) | [PR #1791](https://github.com/GreedyBear-Project/GreedyBear/pull/1791): Add accessible name to ScrollToTopButton | React, Accessibility | **Closed** (Superseded by #1795) |

---

### Issues & Bug Reports Authored (14 Total: 7 Open, 7 Closed)

| Project | Issue | Focus / Topic | Status | Related PR |
|---|---|---|---|---|
| [openvinotoolkit/model_server](https://github.com/openvinotoolkit/model_server) | [Issue #4695](https://github.com/openvinotoolkit/model_server/issues/4695) | `stou64()` accepts negative values preceded by whitespace | **Closed** | [PR #4694](https://github.com/openvinotoolkit/model_server/pull/4694) (Merged) |
| [openvinotoolkit/model_server](https://github.com/openvinotoolkit/model_server) | [Issue #4717](https://github.com/openvinotoolkit/model_server/issues/4717) | MediaPipe session calculator silently accepts malformed `servable_version` values | **Open** | [PR #4726](https://github.com/openvinotoolkit/model_server/pull/4726) (Open) |
| [AOSSIE-Org/Rein](https://github.com/AOSSIE-Org/Rein) | [Issue #441](https://github.com/AOSSIE-Org/Rein/issues/441) | Production build (`npm run build`) fails due to unresolved `react-icons` imports | **Closed** | [PR #442](https://github.com/AOSSIE-Org/Rein/pull/442) (Merged) |
| [AOSSIE-Org/Rein](https://github.com/AOSSIE-Org/Rein) | [Issue #454](https://github.com/AOSSIE-Org/Rein/issues/454) | Stale `DataChannel` event listeners on reconnect trigger false disconnect state | **Open** | [PR #455](https://github.com/AOSSIE-Org/Rein/pull/455) (Open) |
| [AOSSIE-Org/BabyNest](https://github.com/AOSSIE-Org/BabyNest) | [Issue #282](https://github.com/AOSSIE-Org/BabyNest/issues/282) | AI appointment rescheduling fails due to missing `user_id` in update payload | **Closed** | [PR #285](https://github.com/AOSSIE-Org/BabyNest/pull/285) (Merged) |
| [AOSSIE-Org/BabyNest](https://github.com/AOSSIE-Org/BabyNest) | [Issue #291](https://github.com/AOSSIE-Org/BabyNest/issues/291) | Unhandled `TypeError` in `RAGService` when `userContext` is null & missing `addMedicine` import | **Open** | [PR #304](https://github.com/AOSSIE-Org/BabyNest/pull/304) (Open) |
| [GreedyBear-Project/GreedyBear](https://github.com/GreedyBear-Project/GreedyBear) | [Issue #1788](https://github.com/GreedyBear-Project/GreedyBear/issues/1788) | `ScrollToTopButton` has no accessible name for assistive technology | **Closed** | [PR #1795](https://github.com/GreedyBear-Project/GreedyBear/pull/1795) (Merged) |
| [GreedyBear-Project/GreedyBear](https://github.com/GreedyBear-Project/GreedyBear) | [Issue #1818](https://github.com/GreedyBear-Project/GreedyBear/issues/1818) | Unmounting first subscriber in `useWidgetData` aborts shared request for remaining subscribers | **Open** | Independent Bug Report |
| [fossasia/voxbento](https://github.com/fossasia/voxbento) | [Issue #998](https://github.com/fossasia/voxbento/issues/998) | API v1 booth and transcription endpoints return 500 instead of 400 on invalid `language_code` | **Open** | [PR #999](https://github.com/fossasia/voxbento/pull/999) (Open) |
| [fossasia/scrum_helper](https://github.com/fossasia/scrum_helper) | [Issue #945](https://github.com/fossasia/scrum_helper/issues/945) | Custom date range displays incorrect dates in report heading in UTC-negative timezones | **Open** | [PR #948](https://github.com/fossasia/scrum_helper/pull/948) (Open) |
| [SK8-infi/Devkriti-Popcorn-frontend](https://github.com/SK8-infi/Devkriti-Popcorn-frontend) | [Issue #8](https://github.com/SK8-infi/Devkriti-Popcorn-frontend/issues/8) | Showing user not found when selecting location | **Closed** | Frontend Bug Report |
| [SK8-infi/Devkriti-Popcorn-frontend](https://github.com/SK8-infi/Devkriti-Popcorn-frontend) | [Issue #9](https://github.com/SK8-infi/Devkriti-Popcorn-frontend/issues/9) | Search functionality not working across listed items | **Closed** | Frontend Bug Report |
| [SK8-infi/Devkriti-Popcorn-frontend](https://github.com/SK8-infi/Devkriti-Popcorn-frontend) | [Issue #10](https://github.com/SK8-infi/Devkriti-Popcorn-frontend/issues/10) | Contact Us page layout and submission issues | **Closed** | Frontend Bug Report |
| [SK8-infi/Devkriti-Popcorn-frontend](https://github.com/SK8-infi/Devkriti-Popcorn-frontend) | [Issue #11](https://github.com/SK8-infi/Devkriti-Popcorn-frontend/issues/11) | Upcoming shows of a movie layout restructuring | **Open** | UI / Layout Improvement |

---

## Detailed contributions

### 1. Intel OpenVINO Model Server: Whitespace-prefixed negative integer parsing in `stou64`

- **Repository:** [openvinotoolkit/model_server](https://github.com/openvinotoolkit/model_server)
- **Pull Request:** [PR #4694](https://github.com/openvinotoolkit/model_server/pull/4694)
- **Associated Issue:** [Issue #4695](https://github.com/openvinotoolkit/model_server/issues/4695)
- **Status:** Merged (26 October 2026)
- **Stack:** C++, String Parsing, GoogleTest

**Problem.** In OpenVINO Model Server's string utilities (`src/stringutils.cpp`), `ovms::stou64()` converts numeric strings to unsigned 64-bit integers (`uint64_t`). To prevent negative values from converting into positive integers, the function checked `!str.empty() && str[0] == '-'`. However, `std::stoull` discards leading ASCII whitespace before evaluating sign characters. As a result, negative numbers with leading whitespace (such as `" -100"` or `"\t-5"`) bypassed the index-zero boundary check and were passed to `std::stoull`, triggering an implicit unsigned modular wrap into values like `18446744073709551516ULL`.

**What I did.** 
- Modified `src/stringutils.cpp` to locate the first non-whitespace character via `str.find_first_not_of(" \t\n\r\f\v")` instead of assuming index `0`. If that character is `-`, the conversion aborts safely and returns `std::nullopt`.
- Expanded the GoogleTest suite in `src/test/stringutils_test.cpp` with test vectors covering whitespace-prefixed negative values (`" -100"`, `"\t-100"`, `"  -5"`), whitespace-prefixed positive integers (`" 100"`), trailing whitespace, empty strings (`""`), and whitespace-only strings (`"   "`).

**Outcome.** Approved and merged directly into `main` by Intel maintainers on 26 October 2026.

---

### 2. Intel OpenVINO Model Server: Validation of MediaPipe `servable_version` inputs

- **Repository:** [openvinotoolkit/model_server](https://github.com/openvinotoolkit/model_server)
- **Pull Request:** [PR #4726](https://github.com/openvinotoolkit/model_server/pull/4726)
- **Associated Issue:** [Issue #4717](https://github.com/openvinotoolkit/model_server/issues/4717)
- **Status:** Open (waiting for review)
- **Stack:** C++, MediaPipe Framework, Bazel, GoogleTest

**Problem.** In the MediaPipe session calculator (`openvinomodelserversessioncalculator.cc`), an ad-hoc local implementation of `stou32()` used `std::stoul(str)` without verifying that the entire input string was consumed. This allowed malformed `servable_version` strings containing decimals, hex prefixes, or trailing alphanumeric characters (such as `"3.9"`, `"12abc"`, or `"0x3"`) to be partially consumed rather than rejected (`"3.9"` silently parsed as version `3`), risking unexpected model version resolution in inference pipelines.

**What I did.**
- Removed the duplicate local `stou32` function and linked the canonical `//src:libovmsstring_utils` library in `src/mediapipe_calculators/ovms/BUILD`.
- Replaced partial string consumption with a strict check against `::ovms::stou32()`. When a supplied version cannot be fully parsed as a non-negative integer or is empty, the calculator logs the offending value and returns `mediapipe::InvalidArgumentError`.
- Authored a regression test fixture (`OpenVINOModelServerSessionCalculatorVersionTest`) in `src/test/mediapipe_framework_test.cpp` using `ParseTextProtoOrDie` to construct minimal calculator graph configs and verify that invalid version inputs fail deterministically during the calculator's `Open()` initialization step without requiring a running model server instance.

**Outcome.** CI builds and automated tests pass with clean status; waiting for maintainer final review.

---

### 3. AOSSIE Rein: Resolving production build failure by migrating to `lucide-react`

- **Repository:** [AOSSIE-Org/Rein](https://github.com/AOSSIE-Org/Rein)
- **Pull Request:** [PR #442](https://github.com/AOSSIE-Org/Rein/pull/442)
- **Associated Issue:** [Issue #441](https://github.com/AOSSIE-Org/Rein/issues/441)
- **Status:** Merged (1 November 2026)
- **Stack:** TypeScript, React, Rolldown / Vite, Biome, Vitest

**Problem.** Running the production build (`npm run build`) in the Vite/Rolldown bundler failed during module resolution. Deep nested import paths from legacy `react-icons` packages (`react-icons/fa`, `react-icons/fa6`, `react-icons/md`) inside `ServerTab.tsx` and `Trackpad/ExtraKeys.tsx` could not be resolved, halting the build.

**What I did.**
- Identified all `react-icons` imports in the codebase and replaced them with standard icons from `lucide-react` (`TriangleAlert`, `VolumeX`, `Volume1`, `Volume2`, `Play`, `Pause`, `SkipBack`, `SkipForward`, `ArrowUp`, `ArrowDown`, `ArrowLeft`, `ArrowRight`, `CornerDownLeft`, `Space`).
- Replaced an ad-hoc CSS rotation workaround on the Enter key icon with Lucide's native `CornerDownLeft` icon.
- Removed the unused `react-icons` package from `package.json` and lockfiles.
- Verified 0 lint errors with Biome across 80 files and verified all 19 unit tests pass in Vitest.

**Outcome.** Reviewed, approved by CodeRabbit and maintainers, and merged into `master` on 1 November 2026.

---

### 4. AOSSIE Rein: Detaching stale `RTCDataChannel` event listeners during WebRTC reconnection

- **Repository:** [AOSSIE-Org/Rein](https://github.com/AOSSIE-Org/Rein)
- **Pull Request:** [PR #455](https://github.com/AOSSIE-Org/Rein/pull/455)
- **Associated Issue:** [Issue #454](https://github.com/AOSSIE-Org/Rein/issues/454)
- **Status:** Open (waiting for review)
- **Stack:** TypeScript, WebRTC DataChannels, React Context, Vitest, React Testing Library

**Problem.** In Rein's screen-mirroring and input streaming client, when a reconnection occurs, `useWebRtcStream` initializes a new `RTCPeerConnection` and establishes replacement data channels. However, the event handlers (`onopen`, `onclose`, `onerror`, `onmessage`) on the previous data channels remained attached. When the old data channel subsequently closed in the background, its `onclose` callback fired and updated the React connection status to `disconnected`, causing an active reconnected session to falsely report as disconnected.

**What I did.**
- Implemented an `unregisterDataChannels()` method in `ConnectionProvider.tsx` that explicitly nullifies event listeners on existing data channels before replacement channels are bound, and exposed it through `ConnectionContext`.
- Integrated `unregisterDataChannels()` into the cleanup and reconnection cycle in `useWebRtcStream.ts`.
- Developed unit test suites in Vitest (`ConnectionProvider.test.tsx` and `useWebRtcStream.test.tsx`) using mocked `RTCDataChannel` instances to verify that listeners are properly cleared and that late-firing callbacks from superseded channels do not modify active connection state.
- Configured `vitest.config.ts` to include `.tsx` pattern matching for component tests.

**Outcome.** CodeRabbit review passed; test suite green with zero regressions; pending maintainer review.

---

### 5. AOSSIE BabyNest: Resolving AI appointment rescheduling failure via `user_id` propagation

- **Repository:** [AOSSIE-Org/BabyNest](https://github.com/AOSSIE-Org/BabyNest)
- **Pull Request:** [PR #285](https://github.com/AOSSIE-Org/BabyNest/pull/285)
- **Associated Issue:** [Issue #282](https://github.com/AOSSIE-Org/BabyNest/issues/282)
- **Status:** Merged (26 October 2026)
- **Stack:** React Native, AsyncStorage, JavaScript

**Problem.** In BabyNest's conversational prenatal care assistant, attempting to update or reschedule an existing medical appointment through the chat interface failed. The `handleAppointmentUpdate` function in `src/services/ConversationContext.js` assembled the update payload for `updateAppointment()` without including the required `user_id` field, causing the backend update request to fail validation.

**What I did.** Retrieved the authenticated user identifier from persistent client storage via `AsyncStorage.getItem('user_id')` and included it in `updatePayload`, with a fallback to `selectedAppointment.user_id` when present.

**Outcome.** Merged into `master` by repository maintainers on 26 October 2026.

---

### 6. AOSSIE BabyNest: Null-safe RAG context handling and missing module imports

- **Repository:** [AOSSIE-Org/BabyNest](https://github.com/AOSSIE-Org/BabyNest)
- **Pull Request:** [PR #304](https://github.com/AOSSIE-Org/BabyNest/pull/304)
- **Associated Issue:** [Issue #291](https://github.com/AOSSIE-Org/BabyNest/issues/291)
- **Status:** Open (waiting for review)
- **Stack:** React Native, RAG Service, Jest

**Problem.** Two runtime issues occurred in the conversational assistant:
1. When users triggered logging actions (weight, blood pressure, symptoms, medication) before pregnancy profile context had finished loading, direct property access on `userContext.current_week` threw an unhandled `TypeError: Cannot read properties of null`.
2. Calling the medication logging method threw `ReferenceError: addMedicine is not defined` because `addMedicine` had not been imported in `RAGService.js`.

**What I did.**
- Added optional chaining across contextual logging methods in `src/services/RAGService.js` (`userContext?.current_week || 12`) to supply baseline defaults when context has not yet resolved.
- Added the missing import for `addMedicine` from `../storage/medicine`.
- Created a Jest test suite (`__tests__/ragUserContextNullSafe.test.js`) mocking storage and background dependencies to verify safe fallback behavior when `userContext` is null.

**Outcome.** CodeRabbit review passed; unit test suite green; under maintainer review.

---

### 7. The Honeynet Project GreedyBear: Accessibility compliance on `ScrollToTopButton`

- **Repository:** [GreedyBear-Project/GreedyBear](https://github.com/GreedyBear-Project/GreedyBear)
- **Pull Request:** [PR #1795](https://github.com/GreedyBear-Project/GreedyBear/pull/1795) *(Superseded PR #1791)*
- **Associated Issue:** [Issue #1788](https://github.com/GreedyBear-Project/GreedyBear/issues/1788)
- **Status:** Merged (27 October 2026)
- **Stack:** React, Accessibility (WCAG), Jest

**Problem.** In GreedyBear's threat intelligence dashboard, the floating `ScrollToTopButton` component rendered an SVG icon inside a `<Button>` without an accessible name (`aria-label` or text node), making it invisible to screen readers and failing WCAG 2.1 accessibility criteria. Additionally, the scroll listener used the deprecated `window.pageYOffset` property.

**What I did.**
- Added an explicit `aria-label="Scroll to top"` attribute to the button in `ScrollToTopButton.jsx`.
- Replaced the deprecated `window.pageYOffset` property with standard `window.scrollY`.
- Authored Jest and React Testing Library tests under `frontend/tests/components/common/` verifying accessible name presence in the accessibility tree, visibility toggling based on scroll thresholds, and click event handling that triggers `window.scrollTo`. *(Closed PR #1791 in favor of #1795 to submit a clean rebased branch with test coverage).*

**Outcome.** Merged into `develop` by maintainers on 27 October 2026.

---

### 8. The Honeynet Project GreedyBear: Request cancellation bug on multi-subscriber widgets

- **Repository:** [GreedyBear-Project/GreedyBear](https://github.com/GreedyBear-Project/GreedyBear)
- **Issue:** [Issue #1818](https://github.com/GreedyBear-Project/GreedyBear/issues/1818)
- **Status:** Open (Bug Report)
- **Stack:** React Hooks, `AbortController`, Concurrency

**Problem.** Diagnosed and documented a concurrency race condition in the custom `useWidgetData` hook. When multiple dashboard widgets subscribe to the same cached query key and in-flight fetch promise, the hook shared a single `AbortController` across all subscribers. When one widget unmounted, its `useEffect` cleanup called `controller.abort()`, which prematurely cancelled the active network request for the remaining mounted widgets and left them in an unhandled error state. Documented reproduction steps and proposed scoping abort controllers per subscriber or using reference-counted cancellation.

---

### 9. FOSSASIA Voxbento: Validating `language_code` parameters in API v1

- **Repository:** [fossasia/voxbento](https://github.com/fossasia/voxbento)
- **Pull Request:** [PR #999](https://github.com/fossasia/voxbento/pull/999)
- **Associated Issue:** [Issue #998](https://github.com/fossasia/voxbento/issues/998)
- **Status:** Open (Merge conflict on upstream `dev` branch)
- **Stack:** Python, FastAPI, Pydantic, Pytest

**Problem.** In Voxbento's audio booth and transcription endpoints, passing an unsupported or invalid `language_code` route or query parameter triggered an unhandled internal exception, returning `HTTP 500 Internal Server Error` instead of a structured client validation error (`HTTP 400 Bad Request`).

**What I did.**
- Implemented a validation helper `_validate_lang()` in `portal/routers/api_v1.py` that validates incoming language codes against supported language options and raises `HTTPException(status_code=400, detail="...")` on invalid values.
- Authored unit tests in `tests/test_api_v1_rooms.py` asserting input boundary enforcement and error response codes.
- Recorded and attached an end-to-end verification screencast demonstrating passing tests, satisfying repository contribution guidelines and removing the `needs-screencast` label.
- Addressed maintainer review feedback from `@Th-Shivam` by ordering `_validate_lang()` after event lookup and RBAC checks across all six route handlers, ensuring invalid event IDs return `404 Event not found` before language validation executes. Added regression tests verifying this precedence.

**Current blocker / status.** Active and complete. Upstream commits on `dev` introduced a merge conflict; rebasing on `dev` and CI workflow run authorization by maintainers are pending.

---

### 10. FOSSASIA Scrum Helper: Preserving custom date ranges across timezones

- **Repository:** [fossasia/scrum_helper](https://github.com/fossasia/scrum_helper)
- **Pull Request:** [PR #948](https://github.com/fossasia/scrum_helper/pull/948)
- **Associated Issue:** [Issue #945](https://github.com/fossasia/scrum_helper/issues/945)
- **Status:** Open (waiting for review)
- **Stack:** JavaScript, Date/Timezone Handling, Automated Testing

**Problem.** When users in negative UTC time zones generated custom sprint summary reports, the report heading displayed dates offset by one day. Client-side date formatting converted date strings using the local browser timezone before rendering the heading, shifting the display date backward across timezone boundaries.

**What I did.** Centralized date formatting in `src/scripts/scrumHelper.js` with an explicit `timeZone: 'UTC'` option in `formatDate()`, ensuring report headings display consistent calendar dates regardless of the user's local operating system timezone. Added automated unit tests in `tests/customDateReportHeading.test.js` verifying date stability across positive, negative, and UTC timezones.

**Outcome.** All pre-merge automated verification pipelines passed (CodeRabbit semantic title validation, linked issue verification, and changeset scope verification); awaiting final maintainer merge.

---

### 11. Devkriti Popcorn Frontend: Component & UI Issue Reports

- **Repository:** [SK8-infi/Devkriti-Popcorn-frontend](https://github.com/SK8-infi/Devkriti-Popcorn-frontend)
- **Issues:**
  - [Issue #8](https://github.com/SK8-infi/Devkriti-Popcorn-frontend/issues/8): `showing user not found when selecting location` (Closed)
  - [Issue #9](https://github.com/SK8-infi/Devkriti-Popcorn-frontend/issues/9): `search not working` (Closed)
  - [Issue #10](https://github.com/SK8-infi/Devkriti-Popcorn-frontend/issues/10): `contact us page` (Closed)
  - [Issue #11](https://github.com/SK8-infi/Devkriti-Popcorn-frontend/issues/11): `upcoming shows of a movie layout to be changed` (Open)
- **Summary:** Documented frontend issues across the application, including state handling errors on location selection, broken search query filtering across catalog items, contact form layout and submission errors, and layout adjustments for movie schedule cards.

---

## Contributing workflow

To add new contributions as they are submitted or merged:

1. Add a row to the [Pull Requests](#pull-requests-10-total-4-merged-5-open-1-superseded) or [Issues Authored](#issues--bug-reports-authored-14-total-7-open-7-closed) table with the project name, link, stack, and status (`Merged`, `Open`, or `Closed`).
2. Update the [Overview](#overview) metric counts to reflect the new total.
3. Append a technical summary under [Detailed contributions](#detailed-contributions) detailing the problem, implementation, maintainer discussions, and current status.
