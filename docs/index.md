# Packages

* [pogo-migrate](https://nrwldev.github.io/pogo-migrate)
    * A migration tool intended for use with `asyncpg` and assists with
      maintaining your database schema (and data if required) as it evolves.
      Pogo supports migrations written in raw sql, as well as python files
      (useful when data needs to be migrated).
* [changelog-gen](https://nrwldev.github.io/changelog-gen)
    * A conventional commit CHANGELOG generator intended to be used in
      conjunction with
      [bump-my-version](https://github.com/callowayproject/bump-my-version) to
      generate changelogs and create release tags.
* [fastapi-problem](https://nrwldev.github.io/fastapi-problem)
    * A set of exceptions and handlers for use in fastapi applications to
      support easy error management and responses. Each exception easily
      marshals to JSON based on the
      [RFC9457](https://www.rfc-editor.org/rfc/rfc9457.html) spec for use in
      api error responses.
