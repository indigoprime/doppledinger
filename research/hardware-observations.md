# Initial hardware observations

Status: photo review only, 5 October 2026. No continuity measurements, power-up or ROM dump is recorded here.

| Item | Working observation | Evidence / qualification |
|---|---|---|
| CPU | Mostek MK3880, Z80 family | Reading of chip markings in discovery photographs; add component location and close-up reference during inventory. |
| Video | Motorola MC6847 | Photo identification; same video family alone does not establish CoCo/Dragon compatibility or design ancestry. |
| TV output | MC1372P | Photo identification; not a programmable music generator. |
| SRAM | Two HM6116P-3 devices, 2 KB each | 4 KB identified capacity; mapping and video access unknown. |
| Sound | No dedicated generator positively identified | Contemporary claims require reconciliation with this board. |
| Firmware | No ROM positively identified | 8 KB BASIC ROM was advertised. Missing firmware cannot yet be assigned to a particular empty socket. |
| Connectors | Three grouped RCA/phono sockets, 9-pin D-sub and card-edge connections discussed | Pinouts and functions unverified. InfoWorld's list is documentary evidence, not a continuity map. |
| Construction | Hand wiring and unfilled sockets | Do not infer prototype status solely from these features. |

A conventional MC6847 256×192 one-bit framebuffer requires 6 KB. Eight-colour capability and maximum resolution refer to different mode constraints. The 4 KB identified on this board does not establish support for every advertised mode.

See [source register](sources.md) and [open questions](open-questions.md). Photographs on the website illustrate the machine; the underside photograph is not evidence for component markings on the other face.
