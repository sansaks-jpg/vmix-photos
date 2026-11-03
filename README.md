# vMix UI/UX Map

This map connects the main interface to all panels opened via buttons, gear icons, menus, tabs, and dropdowns. Every screenshot link is clickable to view the corresponding image in the `screenshots` folder.

The mapped session is based on **vMix Trial 29.0.0.48 x64** with two blank inputs. Screenshots document the screen state during inspection; this documentation does not duplicate network values or registration credentials that may be visible in the captures.

## Main Pathways

| From Main Screen | Click / Action | Result & Screenshot |
|---|---|---|
| [Main Screen](screenshots/00-main.jpg) | Settings (top right) | General settings and software configuration tabs (see Section 2). |
| [Main Screen](screenshots/00-main.jpg) | Add Input (bottom left) | Source selector and input-specific configuration forms (see Section 3). |
| [Main Screen](screenshots/00-main.jpg) | Gear icon next to Record | Record Setup and format options (see Section 4). |
| [Main Screen](screenshots/00-main.jpg) | External button or gear icon | External output menu and routing settings (see Section 5). |
| [Main Screen](screenshots/00-main.jpg) | Stream button or gear icon | Stream profiles, destinations, quality presets, Advanced settings, and status (see Section 6). |
| [Main Screen](screenshots/00-main.jpg) | MultiCorder gear icon | MultiCorder recording settings and format options (see Section 7). |
| [Main Screen](screenshots/00-main.jpg) | Playlist gear icon | Playlist setup and playback controls (see Section 8). |
| [Main Screen](screenshots/00-main.jpg) | Overlay (bottom right) | Overlay Settings, channel numbers, types, transition effects, and PIP (see Section 9). |
| [Main Screen](screenshots/00-main.jpg) | Menu icon (bottom right) | Data Sources, Triggers, Audio Bus Manager, companion applications, and Web Controller (see Section 10). |

Visible main screen controls include Preview and Output monitors, Quick Play / Cut / Fade / FTB transitions, eight overlay channel buttons, the input list, the audio mixer, as well as New / Open / Save controls and Basic mode toggle. Transition buttons, overlay triggers, ON AIR, Start Record, Start Stream, MultiCorder, and External were not executed during this inspection.

## 1. Main Interface

- [vMix Main Interface](screenshots/00-main.jpg) — Panel and button layout when the project contains blank inputs.
- [Basic Mode](screenshots/28-basic-mode.jpg) — Display layout after toggling Basic Mode. Settings were restored to default layout after capturing.
- [Grid Icon / Shortcuts Window Trigger](screenshots/27c-main-grid-icon.jpg) — Location of the grid icon that opens the Shortcuts window.
- [Shortcuts Window](screenshots/27d-shortcuts-window.jpg) — Shortcut cards, Web Controller button, and Edit interface.
- Statistics: [Main Tab](screenshots/27a-statistics.jpg), [Overview](screenshots/27b-statistics-overview.jpg), [SRT](screenshots/27b-statistics-srt.jpg), [Encoders](screenshots/27b-statistics-encoders.jpg), and [OMT](screenshots/27b-statistics-omt.jpg). The Reset button was not pressed.

## 2. Top-Right Settings

Click **Settings** at the top right of the main interface. The left navigation pane switches between the following pages:

- [Display](screenshots/01-settings-display.jpg) — Theme, Preview/Output colors, master frame rate, output size/aspect ratio, fullscreen monitors, and input display size.
- [Outputs / NDI / OMT / SRT](screenshots/02-settings-outputs.jpg).
- [Options](screenshots/03-settings-options.jpg).
- [Performance](screenshots/04-settings-performance.jpg).
- [Decoders](screenshots/05-settings-decoders.jpg).
- [Recording](screenshots/06-settings-recording.jpg).
- [External Output](screenshots/07-settings-external-output.jpg), featuring four tabs/views: [1](screenshots/07-settings-external-output.jpg), [2](screenshots/07a-settings-external-2.jpg), [3](screenshots/07b-settings-external-3.jpg), [4](screenshots/07c-settings-external-4.jpg).
- [Audio](screenshots/08-settings-audio.jpg) and [Audio Outputs](screenshots/09-settings-audio-outputs.jpg).
- [Web Controller](screenshots/10-settings-web-controller.jpg) and [Tally Lights](screenshots/11-settings-tally-lights.jpg).
- [Shortcuts – All](screenshots/12-settings-shortcuts.jpg), followed by filters for [Keyboard](screenshots/12a-settings-shortcuts-keyboard.jpg), [MIDI](screenshots/12b-settings-shortcuts-midi.jpg), [Surface](screenshots/12c-settings-shortcuts-surface.jpg), and [Joystick](screenshots/12d-settings-shortcuts-joystick.jpg).
  - [MIDI Settings](screenshots/12d-settings-midi-devices.jpg) opens the MIDI device list (currently empty). [Channel Mappings](screenshots/12e-settings-midi-channel-mapping.jpg) displays controller and channel assignments.
  - [Templates](screenshots/12f-settings-shortcut-templates.jpg) lists device templates along with Display as, Import, Export, Save Graphic, Apply, and Close. Apply was not clicked.
  - [Find Control](screenshots/12g-settings-shortcuts-find-control.jpg) listens for keyboard/controller input; no keys were pressed.
  - [Add Shortcut – General](screenshots/12h-settings-shortcut-add-general.jpg) contains Key/Control, Function, Duration, Input, Title, Description, Display, and Web Controller/Telestrator toggles. [Add Shortcut – Advanced](screenshots/12i-settings-shortcut-add-advanced.jpg) adds keyboard triggers. The dialog was closed via Cancel.
- [Activators](screenshots/13-settings-activators.jpg), [Scripting](screenshots/14-settings-scripting.jpg), [Alerts](screenshots/15-settings-alerts.jpg), and [About](screenshots/16-settings-about.jpg).
- [Show Advanced Settings Warning](screenshots/17-settings-advanced-warning.jpg). Inspection stopped at this warning and did not proceed into the Advanced panel.

Import, Export, Default, OK, and Cancel buttons are located at the bottom of the Settings window. No shortcut or preference changes were saved during inspection.

## 3. Bottom-Left Add Input

Click **Add Input** to open the Input Select window. Available input types and corresponding screenshots:

- [Video](screenshots/23-add-input-video.jpg), [DVD](screenshots/23a-add-input-dvd.jpg), [List](screenshots/23b-add-input-list.jpg), and [Camera](screenshots/23c-add-input-camera.jpg).
- [NDI / OMT / Desktop Capture](screenshots/23d-add-input-ndi-desktop.jpg), including [Local Desktop Capture](screenshots/23d1-add-input-local-desktop.jpg).
- Stream: [Basic Panel](screenshots/23e-add-input-stream-srt.jpg), [Protocol Type Menu](screenshots/23e1-stream-type-menu.jpg), [RTSP TCP](screenshots/23e2-stream-rtsp-tcp.jpg), [Advanced Type Menu](screenshots/23e3-stream-type-menu-tcp.jpg), [SRT Caller](screenshots/23e4-stream-srt-caller.jpg), [Base SRT Panel](screenshots/23e5-stream-srt-base.jpg), [Other Type Menu](screenshots/23e6-stream-type-menu.jpg), [VLC Prompt](screenshots/23e8-vlc-install-prompt.jpg), [SRT Listener](screenshots/23e9-stream-srt-listener.jpg), and [SRT Rendezvous](screenshots/23ea-stream-srt-rendezvous.jpg). Visible protocols include RTSP UDP/TCP, Transport Stream UDP/TCP/TCP Pull, VLC, and three SRT modes.
- [Instant Replay](screenshots/23f-add-input-instant-replay.jpg), [Image Sequence / Stinger](screenshots/23g-add-input-image-sequence.jpg), and [Video Delay](screenshots/23h-add-input-video-delay.jpg).
- [Image](screenshots/23i-add-input-image.jpg), [Photos](screenshots/23j-add-input-photos.jpg), [PowerPoint](screenshots/23k-add-input-powerpoint.jpg), [Colour](screenshots/23l-add-input-colour.jpg), [Audio](screenshots/23m-add-input-audio.jpg), and [Audio Input](screenshots/23n-add-input-audio-input.jpg).
- [Title](screenshots/23o-add-input-title.jpg), [Virtual Set](screenshots/23p-add-input-virtual-set.jpg), [Web Browser](screenshots/23q-add-input-web-browser.jpg), [Video Call](screenshots/23r-add-input-video-call.jpg), [Zoom](screenshots/23u-add-input-zoom-selected.jpg), and [Telestrator](screenshots/23w-add-input-telestrator.jpg).
- [Scrolled Input List](screenshots/23v-add-input-list-scrolled.jpg) shows Telestrator located at the bottom of the list. [vMix Call Message](screenshots/23t-vmix-call-error-closed.jpg) indicates the call server is disconnected. Zoom displays a note that the plugin is not installed; no download was initiated. Telestrator prompts to enable the Web Controller feature first.

All Add Input windows were closed without adding inputs. The OK button was not pressed.

## 4. Record Settings

The gear icon next to Record opens [Record Setup](screenshots/18-record-setup.jpg). Format options were captured individually:

- [AVI](screenshots/18a-record-avi.jpg)
- [WMV](screenshots/18b-record-wmv.jpg)
- [WMV Streaming](screenshots/18c-record-wmv-streaming.jpg)
- [MP4](screenshots/18d-record-mp4.jpg)
- [FFMPEG](screenshots/18e-record-ffmpeg.jpg)
- [vMix AVI](screenshots/18f-record-vmix-avi.jpg)
- [Output 2](screenshots/18g-record-output2.jpg)

Record Setup also displays secondary output settings and WAV audio recording controls. No recording sessions were initiated.

## 5. External Settings

- [External Setup Menu](screenshots/19-external-setup-menu.jpg) displays output routes and access to configuration.
- [External Destination Menu](screenshots/19a-external-menu-destination.jpg) reveals Output 2/3/4 submenus, SRT, and NDI/OMT/SRT output setup pages.

No external outputs were enabled.

## 6. Stream Settings

- [Stream Panel](screenshots/20-stream-settings.jpg) is the main streaming profile configuration window.
- Destination slots: [Slot 2](screenshots/20a-stream-target-2.jpg), [Advanced](screenshots/20b-stream-advanced.jpg), [Slot 3](screenshots/20c-stream-target-3.jpg), [Slot 4](screenshots/20d-stream-target-4.jpg), and [Slot 5](screenshots/20e-stream-target-5.jpg).
- [View Status](screenshots/20f-stream-status.jpg) opens the streaming status monitor.

Profiles can be selected, added, or deleted from the top controls; all five destination slots have their own discrete configurations. Start All and individual Start buttons were not clicked.

## 7. MultiCorder Settings

- [MultiCorder Panel](screenshots/21-multicorder-settings.jpg).
- Formats: [AVI](screenshots/21a-multicorder-avi.jpg), [vMix AVI](screenshots/21b-multicorder-vmix-avi.jpg), [MKV](screenshots/21c-multicorder-mkv.jpg), [MP4](screenshots/21-multicorder-settings.jpg), and [FFMPEG](screenshots/21d-multicorder-ffmpeg.jpg).

MultiCorder was not started and no files were recorded.

## 8. Playlist Settings

- [Playlist Setup](screenshots/22-playlist-settings.jpg) displays an empty playlist, source selector, add/delete, reorder, Loop, Begin from selected, Clear Overlays, Manual Mode, and Start controls.

No media items were added and playback was not run.

## 9. Overlay Settings & Options

- [Overlay Settings](screenshots/24-overlay-menu.jpg) is the initial configuration panel.
- [Number](screenshots/24a-overlay-number-menu.jpg) selects Overlay 1–8 or Stinger 1–8.
- [Type](screenshots/24b-overlay-type-menu.jpg) selects Fullscreen or Picture in Picture.
- [Picture in Picture](screenshots/24c-overlay-picture-in-picture.jpg) displays size/position, zoom, pan, rotation, and border options.
- [Effect](screenshots/24d-overlay-effect-menu.jpg) lists transition effects, including Fade, Zoom, Wipe, Slide, Fly, Cube, Merge, Cut, and variations.
- [Stinger](screenshots/24e-overlay-stinger-menu.jpg) displays Stinger input source options. Since no Stinger input has been configured yet, only None is available.

Picture in Picture was briefly selected solely to map the panel layout and then cancelled. No overlays were sent to Output.

## 10. Additional Tools & Menus

### More Menu

- [More Menu](screenshots/25-main-more-menu.jpg) and [Menu Detail](screenshots/25a-main-more-menu-detail.jpg) link to Data Sources, Triggers, Audio Bus, vMix Social, GT Title Designer, vMix Video Tools, Media Converter, Diagnostics, and Web Controller.

### Data Sources, Triggers, and Audio Bus

- [Data Sources Manager](screenshots/25b-data-sources.jpg), [Add Menu](screenshots/25c-data-sources-add-menu.jpg), and [Options Detail Menu](screenshots/25d-data-sources-options-detail.jpg).
- Source configuration forms: [Excel/CSV](screenshots/25e-data-source-excel-csv-config.jpg), [Google Sheets](screenshots/25f-data-source-google-sheets.jpg), and [JSON](screenshots/25g-data-source-json.jpg). Other types visible in the Add menu include RSS, Text, XML, ZoomChat, Import, Export, and Remove All. No data sources were added.
- [Triggers Manager](screenshots/25h-triggers-manager.jpg) shows an empty list; Go To Input Settings is inactive.
- [Audio Bus Manager](screenshots/25i-audio-bus-manager.jpg), [Bus Selection Menu](screenshots/25j-audio-bus-menu.jpg), and [Lower Bus Menu](screenshots/25k-audio-bus-menu-lower.jpg). The routing matrix has no inputs assigned.

### Companion Applications

- [vMix Social](screenshots/25m-vmix-social-current.jpg) displays social services and title controls. A [Windows Security Alert](screenshots/25l-vmix-social.jpg) appeared upon launching; neither Allow nor Cancel was selected and no social services were enabled.
- [GT Title Designer](screenshots/25n-gt-title-designer.jpg) opened with a blank document. Ribbon tabs: [Home](screenshots/25o-gt-home.jpg), [Styles](screenshots/25o-gt-styles.jpg), [Format](screenshots/25o-gt-format.jpg), [Effects](screenshots/25o-gt-effects.jpg), [Animations](screenshots/25o-gt-animations.jpg), [Data](screenshots/25o-gt-data.jpg), and [File Menu](screenshots/25p-gt-file-menu.jpg). No titles were edited.
- [vMix Video Tools](screenshots/25q-vmix-video-tools.jpg), [Task Menu](screenshots/25r-video-tools-task-menu.jpg), [Create Image Sequence](screenshots/25s-video-tools-image-sequence.jpg), and [Repair vMix AVI](screenshots/25t-video-tools-repair-avi.jpg). No files were processed.
- [Media Converter](screenshots/25u-media-converter.jpg) and [Quality Menu](screenshots/25v-media-converter-quality-menu.jpg). Queue is empty; no conversions were started.
- [vMix Diagnostics](screenshots/25w-vmix-diagnostics.jpg) and [GPU Menu](screenshots/25x-vmix-diagnostics-gpu-menu.jpg). Start Scan was not clicked.

### Web Controller

Opening **Web Controller in Browser** from the More menu accesses the following local endpoints:

- [Shortcuts](screenshots/25y-web-shortcuts.jpg)
- [Controller](screenshots/25z-web-controller.jpg)
- [Tally](screenshots/26a-web-tally.jpg)
- [Titles](screenshots/26b-web-titles.jpg)
- [LiveLAN](screenshots/26c-web-livelan.jpg)
- [Telestrator](screenshots/26d-web-telestrator.jpg)

Shortcut/Controller cards were not pressed, Tally and Titles were empty, LiveLAN had no active video feed, and Telestrator reported as inactive.

## Inspection Scope & Boundaries

- Advanced Settings panel was not opened because vMix displays a warning prompt to proceed; the warning screenshot is documented in the Settings section.
- Several screens inherently depend on connected inputs, physical hardware devices, plugins, or active streaming services. Empty or disconnected states shown above reflect this session's initial baseline.
- Pre-existing configuration values remain visible in their original screenshot captures; no proprietary or environment-specific values have been transcribed into this map.
