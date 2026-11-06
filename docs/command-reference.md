# Local prototype command reference

The following commands are implemented in the local prototype. Their application
source will be published in later milestones.

| Spoken phrase | Intended action |
| --- | --- |
| computer open chrome | Request a Chrome launch |
| computer open visual studio code | Open the project directory in VS Code |
| computer open notepad | Request a Notepad launch |
| computer open calculator | Request a Calculator launch |
| computer open project folder | Open the project directory in File Explorer |
| computer stop listening | Stop microphone capture |

The user starts listening explicitly and speaks a complete phrase before pausing.
Partial recognition results are displayed but do not launch applications.
Unsupported phrases produce a no-action response. Repeated identical actions
within three seconds are suppressed. Stop prevents queued transcripts from
triggering additional actions.

A successful launch request does not independently prove that the application's
window appeared. Recognition accuracy depends on microphone quality and speech.
