---
source_id: SRC-rfc6749-oauth2
title: "RFC 6749: The OAuth 2.0 Authorization Framework"
creators:
  - Internet Engineering Task Force (IETF); D. Hardt, Editor; Microsoft
url: https://www.rfc-editor.org/rfc/rfc6749
date_or_version: "October 2012"
kind: standard
quality_class: Q1
retrieved: 2026-10-01
parse_status: summary-extracted
capture_status: not-captured
rights_status: unverified
archive_manifest: "[[ARC-rfc6749-oauth2]]"
supersedes:
superseded_by:
used_by_workstreams:
  - WS07
  - WS09
---

# Source record: RFC 6749: The OAuth 2.0 Authorization Framework

## Metadata

| Field | Value |
|---|---|
| Source ID | SRC-rfc6749-oauth2 |
| Title | RFC 6749: The OAuth 2.0 Authorization Framework |
| Creators or publisher | Internet Engineering Task Force (IETF); D. Hardt, Editor; Microsoft |
| URL | <https://www.rfc-editor.org/rfc/rfc6749> |
| Date or version | October 2012 |
| Kind | standard |
| Quality class | Q1. Standards-track RFC. See [[Source-Quality-Classes]]. |
| Retrieved | 2026-10-01 |

## Summary

The OAuth 2.0 authorization framework enables a third-party application to obtain limited access to an HTTP service on behalf of a resource owner or on its own behalf. It introduces an authorization layer that separates the client from the resource owner and uses access tokens instead of the resource owner's credentials. The specification defines four authorization grant types: authorization code, implicit, resource owner password credentials, and client credentials. OAuth 2.0 is designed for use with HTTP and replaces and obsoletes the OAuth 1.0 protocol described in RFC 5849.

Extraction note: the summary and evidence below were extracted from the retrieved page text on 2026-10-01 by an AI assistant. They state what the page states, they have not been independently verified, and they need a second-pass review before any claim beyond the evidence block is labelled FACT.

## Parsed evidence

- OAuth defines four roles: resource owner, resource server, client, and authorization server. ^ev-1
- Access tokens represent specific scopes, durations, and other access attributes, and are used to access protected resources. ^ev-2
- Refresh tokens are used to obtain new access tokens and are intended for use only with authorization servers. ^ev-3
- The authorization code grant is optimized for confidential clients and can issue both access tokens and refresh tokens. ^ev-4
- The implicit grant issues an access token directly, does not support refresh tokens, and does not include client authentication. ^ev-5
- The client credentials grant type can only be used by confidential clients. ^ev-6

## Evidence locations

- Page: <https://www.rfc-editor.org/rfc/rfc6749>. Section-level locators are pending a full parse.

## Limitations

The interaction between the authorization server and resource server is beyond the scope of this specification. OAuth 2.0 leaves some components partially or fully undefined, including client registration, authorization server capabilities, and endpoint discovery.

- Parse status is summary-extracted. The full text has not been parsed into this record.

## Conflicts

None recorded. No cross-source comparison has been performed yet.

## Rights and access

Rights status: unverified. No full text is reproduced here. See [[ARC-rfc6749-oauth2]] for capture status.

## Relationships

- Archive manifest: [[ARC-rfc6749-oauth2]]
- Registry: [[Source-Registry]]
- Cited by vault notes: [[Credential-Broker]], [[WS07-Identity-and-Credential-Delegation]], [[WS09-Tool-Protocols-and-Gateway]]

## Workstream usage

- [[WS07-Identity-and-Credential-Delegation]]
- [[WS09-Tool-Protocols-and-Gateway]]

## Verification log

| Date | Action | Result |
|---|---|---|
| 2026-10-01 | Page text retrieved and key statements extracted | summary-extracted |
