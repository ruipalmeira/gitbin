# Release Notes
## Current Version: `v2.1.1`

### Added:
  [`v2.1.1`]
  - 1
  - 2
     
  [`v2.1.0`]
  - 1 
  - 2
     

  [`v2.0.0`]
  - Added color option to dispenser navigation buttons
  - Added fontWeight options to dispenser header
  - Updated translations
  - Refactored UI/UX of schedules
  - Show slot end time `via-guide` ​🚀​
  - Show slot end time in overview step `via-guide` ​🚀​
  - Show slot capacity percentage `via-guide` ​🚀​
  - SAdd video duration column (edit-playlist)

### Fixes:
  [`v2.0.0`]
  - Use moment() in current time `via-guide` ​🚀​
  - Fixed date label calculation for date-time widget  
  - Added `totalDays` configuration for weather widget
  - Set image for umbrella card.
  - Round the temperature value to integer `api` (weather widget)
  - Updated application favicon 
  - Video preview (edit-playlist)
  

### Devices: 
- **Dispenser**
  - Fix icon position navigation-buttons
  - Added color option
  - Added fontWeight options to header
- **Terminal**
  - Fix responsiveness of some elements
- **Launcher** 
     - Listen debug-menu:logout event from electron (internal)
- **Widget Player**
     - Refactor `BlinkingTicket` method (internal)

### Backoffice: 
 - Fix sentry error - Cannot read properties of null (reading 'email') (internal)
 - #### Dashboard
    -  Listen table updates (internal)
    -  Refactor table selector - Fix spotlight icons - Update dashboard title translation
    -  Hide statistics & old dashboard for `ise2023.moviik.in` (internal)
    -  Add scroll to charts
    -  Fix dashboard selector
 - #### Charts
   - change scroll to table only 
   - small layout and translation fix
   - fix syntax and refresh button fix
   - fixes, etc from review (internal)
   - changed to match design (internal)
 - #### Devices
   - Fix position of dropdown-menu (added in `v2.1.0`)
 - #### Assets
   - **i18n**
     - Update translations
     - Add/update translations
   - **edit-Playlist**
     - Refactor `convertSeconds` (interal)
     - Added video duration column
     - Fixed video preview 
   - **Playlists**
     - Refactor `artifacts.thumbnail.frames` path (internal)
 - #### Widgets
  
   
 - #### API
   - weather: Round the temperature value to integer 
   - hide no internet connection snackbar (internal)
 - #### APPS
   - small fixes (internal)
   - set image for umbrella card
 - #### Utils
   - constants: Add/implement `weatherServiceDefaultTotalDays` const (internal)
 - #### Via-Guide
   - Access times are now represented as a 3x3 grid 
   - Show slot end time in booking-details
   - new-booking: Return slot in `getNearestSlotFromDeparture` (internal)
   - new-booking: Show slot end time in overview step 
   - slot-register: Show slot capacity percentage 
   - use moment in current time
   - change to reflect requested changes (internal)