# Awesome JSDoc [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A list of awesome [jsdoc](https://jsdoc.app/) <sub><sup>([GitHub](https://github.com/jsdoc/jsdoc))</sup></sub> plugins, resources, etc.

## Contents

- [Markdown](#markdown)
- [Linting](#linting)
- [Parsing and Stringifying](#parsing-and-stringifying)
  - [Type parsing](#type-parsing)
- [Schema usage](#schema-usage)
- [Type checking](#type-checking)
- [Visualizations](#visualizations)

## Markdown

- [Official Markdown plugin](https://jsdoc.app/plugins-markdown.html) (converting Markdown syntax within jsdoc when building jsdoc)
- [jsdoc-to-markdown](https://github.com/jsdoc2md/jsdoc-to-markdown) (Generating Markdown docs from JSDoc)
- [jsdoc-md](https://github.com/jaydenseric/jsdoc-md) (Generating Markdown docs from JSDoc)

## Linting

- [eslint-plugin-jsdoc](https://github.com/gajus/eslint-plugin-jsdoc) - ESLint rules for JSDoc blocks.

## Parsing and Stringifying

- [comment-parser](https://github.com/syavorsky/comment-parser) - JSDoc-*like*
  parsing and stringifying (to be semantically aware of jsdoc's tags, you will
  need to supply a custom parser like [in eslint-plugin-jsdoc](https://github.com/gajus/eslint-plugin-jsdoc/blob/master/src/iterateJsdoc.js#L28-L85)).
- [@es-joy/jsdoccomment](https://github.com/es-joy/jsdoccomment) - Allows
  JSDoc-aware tag semantics on top of `comment-parser`. Also has a number of
  utilities, e.g., converting parser AST to ESLint AST and VisitorKeys.
- [@es-joy/jsdoc-eslint-parser](https://github.com/es-joy/jsdoc-eslint-parser) - A
  proof-of-concept ESLint parser integrating `@babel/eslint-parser`,
  `comment-parser` (via `@es-joy/jsdoccomment`), and `jsdocttypeparser`.

### Type parsing

- [jsdoc-type-pratt-parser](https://github.com/simonseyock/jsdoc-type-pratt-parser)
- [jsdoctypeparser](https://github.com/jsdoctypeparser/jsdoctypeparser) - JSDoc type
  parser/stringifier/traverser used in `eslint-plugin-jsdoc` which also supports
  some TypeScript.
- [catharsis](https://github.com/hegemonic/catharsis) - JSDoc type parser used
  within jsdoc itself.

## Schema usage

- [json-schema-to-jsdoc](https://github.com/n3ps/json-schema-to-jsdoc) - Converts
  from [JSON Schema](http://json-schema.org/) to JSDoc.
- [jsdoc-jsonschema](https://github.com/brettz9/jsdoc-jsonschema) - Converts from
  jsdoc to [JSON Schema](http://json-schema.org/) (early in project, but aims to
  use standard `@typedef`).

## Type checking

- [bycontract](https://github.com/dsheiko/bycontract/) - Validate structures with
  jsdoc expressions.
- [eslint-plugin-typelint](https://github.com/yarax/eslint-plugin-typelint) - Allows
  JSON Schema (or Redux reducer) to be pointed to by jsdoc types with
  usage type-checked.
- [tern](https://github.com/ternjs/tern) - Checking type usage against jsdoc.
  (Also interesting for notion of implicit typing--might there be a static
  but implicitly typed, ESLint-enforced subset of JavaScript (like `asm.js`)
  which can compile to more performant code without need to pollute code with
  types everywhere?.)

## Visualizations

- [jsdoc2diagram](https://github.com/amcmillan01/jsdoc2diagram) - Create (D3)
  diagram from your project's jsdoc.
