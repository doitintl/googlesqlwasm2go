# googlesqlwasm2go

wasm2go sources for googlesql.wasm.

**DoiT fork** (`github.com/doitintl/googlesqlwasm2go`): the engine of
`github.com/doitintl/go-googlesql`, regenerated from GoogleSQL 2026.01.1 with
two extra bridge entry points (`Inv_9000_0`, `Inv_9000_1`: the analyzer's
default time zone by name). The module path is the fork's own, so
`go-googlesql`'s generated bridge imports it directly. How it is produced:
`REGENERATION.md` in `github.com/doitintl/go-googlesql`. `make verify` checks
the tree against `googlesql_wasm2go.sha256`.
