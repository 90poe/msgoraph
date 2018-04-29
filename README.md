# msgoraph

[![Documentation](https://godoc.org/github.com/mhoc/msgoraph?status.svg)](http://godoc.org/github.com/mhoc/msgoraph)

A zero dependency Go Client for [Microsoft's Graph API](https://developer.microsoft.com/en-us/graph/docs/concepts/overview). This is built and distributed under all of the philosophies of [vgo](https://research.swtch.com/vgo) for future compatibility, but should work with a simple `go get`, `dep`, or your package management tool of choice until `vgo` is stable. 

## Disclaimers

This library is completely unaffiliated with Microsoft.

This library is pre-release, under active development, and has no tests. We will do our best to ensure that tagged releases are stable enough to use the functionality they export, but bugs could happen. 

This library is in pre-release, and as such the Go Import Compatibility Rule does not apply. Backward-incompatible changes should be expected between all tagged versions and commits. 

## Supported Operations

- `Users :: Create`
- `Users :: Delete`
- `Users :: Get`
- `Users :: List`
- `Users :: Update`
