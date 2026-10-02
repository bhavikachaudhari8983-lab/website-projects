# Bhavika's website projects

Clean source snapshots for independent student website concepts and prototypes. These archives preserve each project's folder structure. Download the relevant ZIP and extract it to inspect the source or run the project. They are source downloads, not online demos.

| Project | What is ready | Remaining limitations |
| --- | --- | --- |
| [COSMOS](cosmos-source.zip) | Astronomy website, section pages, search, illustrated gallery, interest selection | Public hosting pending; institutional approval, event dates and real registrations not claimed |
| [Campus Relay](campus-relay-source.zip) | Browser-local reporting, filtering, simulated progress, confirmation and persistence | No real dispatch; production backend requires configured authentication, database/storage and responder partners |
| [AI Agent Studio](ai-agent-source.zip) | Examples, sandboxed preview, manual code editing, version history and export | Custom generation uses a visitor's API account; live provider flow untested in this batch |
| [Riders Hub](riders-hub-source.zip) | Public sample ride pages, disabled demo account collection, existing member workflow source | Live Supabase setup and integration tests pending; Sites hosting adaptation still required |
| [Portfolio](portfolio-source.zip) | Responsive project index with status labels and available source link | Hosting and remaining public demo URLs pending |
| [VoltGuard](voltguard-source.zip) | Interactive fictional energy dashboard and observation-mode firmware/docs | No hardware connection, completed pilot or measured savings claimed |

The originals are preserved. Expense tracker and Pro-Karters are excluded. ApnaScene is already publicly hosted; its private repository and real database records are not included in these downloads. Aavira's existing private Site still needs sign-in and source review before publication.

## Verification

Six app builds passed (COSMOS, Campus Relay, AI Agent Studio, Riders Hub, portfolio and the separate ApnaScene copy). Campus Relay and AI Agent Studio pass lint and TypeScript checks. Riders Hub passes build, lint and all six existing tests, including PostgreSQL role permissions and the registration-to-check-in workflow. The portfolio passes build and lint. COSMOS passes lint with 11 advisory image-optimization warnings. VoltGuard is a buildless static demo.

Browser verification confirmed Campus Relay's report → acceptance → work → proposed fix → confirmation flow and persistence after refresh. AI Studio's website example rendered in its sandbox. Other preview checks are documented in the preparation report. No live API-provider, cloud member-authentication, operational responder, or hardware tests are claimed.

## Publication status

The updated demos are not deployed. Automatic approval rejected the credential handoff required by the Sites source/publishing helper. No hosting audience was changed. The local previews work only on Bhavika's computer while their servers run.

The source snapshots exclude environment files, credentials, caches, dependency folders, generated build output (except VoltGuard's hand-authored static page) and account-specific hosting IDs. Local binding names are retained in a sanitized `.openai/hosting.json`; register or restore the original Sites identity before cloud deployment. A focused scan found no matching common API-key, token or private-key patterns; this is not a comprehensive security audit.

COSMOS content points to the [university club source](https://mitwpu.edu.in/cosmos), and its publication copy uses original SVG illustration rather than university photographs/logos. Representative Riders Hub photo sources are credited in its media file; no photos are represented as actual club rides.
