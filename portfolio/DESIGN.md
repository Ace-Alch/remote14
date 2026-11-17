# Remote14: design record

## Purpose

Control a personal iPhone through Shortcuts commands, an email receiver and a web controller.

## Elements

| Element | Documentation boundary |
| :-- | :-- |
| Controller draft | Included in the stated project scope. Implementation details need the corresponding source or design file. |
| Email message | Included in the stated project scope. Implementation details need the corresponding source or design file. |
| Receiver shortcut | Included in the stated project scope. Implementation details need the corresponding source or design file. |
| Command engine | Included in the stated project scope. Implementation details need the corresponding source or design file. |
| Reply or history | Included in the stated project scope. Implementation details need the corresponding source or design file. |

## Technical stack

- iPhone Shortcuts
- Email
- Web controller
- Automation

## Boundaries

A web controller that creates an email draft does not prove that the command was sent or executed. Locked-screen operation and Silent switch behavior require tests on the target iPhone. Remove addresses, shared keys and personal history from any public source package.

## Decisions to recover

Record each design decision with its problem, selected option, rejected options and supporting artifact. Keep the original model or source revision with the record.
