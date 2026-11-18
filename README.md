# hbb_common – TRMM Desktop fork (`trmm-desktop`)

Unofficial fork of [rustdesk/hbb_common](https://github.com/rustdesk/hbb_common),
the common library of [RustDesk](https://github.com/rustdesk/rustdesk). It is
not affiliated with the RustDesk team.

It is used by [TRMM Desktop](https://github.com/andrewsbejatto/rustdesk/tree/trmm-desktop),
a RustDesk fork for Tactical RMM.

## The only change

`APP_NAME` is `TRMMDesktop` (`src/config.rs`). The app name drives the service
name, install folders, configuration folder and URI scheme. With it, TRMM
Desktop can be installed next to a regular RustDesk without either one
touching the other.

Everything else is the upstream code. Same license terms as the upstream
`rustdesk/hbb_common` repository.
