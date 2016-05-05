# Yacc [DEPRECATED]

This project is deprecated and remains only to allow old versions of
CockroachDB to build. CockroachDB uses the go yacc tool as of
https://github.com/cockroachdb/cockroach/commit/1f41042.

This is a fork of the go yacc tool with minor tweaks to the hardcoded
constants to allow larger grammar sizes (i.e. grammars with more than
2000 states).
