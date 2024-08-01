# Packages

* [pogo-migrate](https://nrwldev.github.io/pogo-migrate)
    * A migration tool intended for use with `asyncpg` and assists with
      maintaining your database schema (and data if required) as it evolves.
      Pogo supports migrations written in raw sql, as well as python files
      (useful when data needs to be migrated).
* [changelog-gen](https://nrwldev.github.io/changelog-gen)
    * A CHANGELOG generator, to detect semantic versioning changes
      from conventional commits, and generate release tags.
* [starlette-problem](https://nrwldev.github.io/starlette-problem)
    * A set of exceptions and handlers for use in Starlette applications to
      support easy error management and responses. Each exception easily
      marshals to JSON based on the
      [RFC9457](https://www.rfc-editor.org/rfc/rfc9457.html) spec for use in
      api error responses.
* [fastapi-problem](https://nrwldev.github.io/fastapi-problem)
    * A set of exceptions and handlers for use in FastAPI applications to
      support easy error management and responses. Each exception easily
      marshals to JSON based on the
      [RFC9457](https://www.rfc-editor.org/rfc/rfc9457.html) spec for use in
      api error responses.
* [auth-aws4](https://nrwldev.github.io/auth-aws4)
    * A usecase agnostic implementation of [AWS4 Sig v4](https://docs.aws.amazon.com/AmazonS3/latest/API/sig-v4-authenticating-requests.html).
