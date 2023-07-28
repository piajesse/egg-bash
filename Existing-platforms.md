# Pros and Cons of existing platforms
## Matrix
Matrix is the backend to a federated messaging platform, it has a bunch of front ends, but the most popular is Element
| Pros  | Cons |
| --- | --- |
| Has a well integrated system for mobile systems  | All Metadata is plain text, including reactions  |
| supports modern E2E like double ratchet  | Can not migrate between home servers easily  |

## Signal
Signal is a messaging app that is designed first for Android, iOS, then their desktop client
| Pros  | Cons |
| --- | --- |
| Has a well designed UX  | Everything is sent to Signals servers which is mostly on AWS  |
| Designed the modern E2E Standard Double Ratchet  | Isn't designed for bots/3rd party clients  |
| Supports Secure Sender  | Desktop client uses the exact same tech as Element, but has much poorer experience |
| All Metadata data other then recipient is encrypted. | Doesn't support markdown |

## iMessage
iMessage is Apple's answer to messaging, it natively supports SMS while also supporting a bunch of more features if both (all if a group chat) use iMessage as its send through apples networks rather then SMS
| Pros  | Cons |
| --- | --- |
| Really clean design | Doesn't support emoji reactions, just a select few reactions |
| "Encrypted" | Uses the same key for all messages in a chat |
| | Closed Source |

## RCS
Google has been trying to get everyone to use RCS to replace SMS, its a bit of a shit show tbh
| Pros  | Cons |
| --- | --- |
| Supports more rich chat features | Requires Google Play Services |
| | Only Google and Samsung have clients |
| | Features are missing on Samsung's client |

## Nextcloud
Nextcloud is a self hosted cloud storage ecosystem
| Pros  | Cons |
| --- | --- |
| Supports Federation/self-hosted infrastructure | Entirely in PHP |
| Supports encrypted file storage | Encrypted files are clunky and slow to upload |
| Supports lots of plugins | Quiet slow, esp on firefox |
