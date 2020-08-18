# Awesome JSDoc [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curation of awesome [JSDoc](https://jsdoc.app/) resources.

## Contents

- [Markdown](#markdown)
- [Linting](#linting)
- [Parsing and Stringifying](#parsing-and-stringifying)
- [Schema usage](#schema-usage)
- [Templates](#templates)
- [Type checking](#type-checking)
- [Visualizations](#visualizations)

## Markdown

- [Official Markdown plugin](https://jsdoc.app/plugins-markdown.html) - Convert
  Markdown-formatted docstrings to HTML in output.
- [jsdoc-to-markdown](https://github.com/jsdoc2md/jsdoc-to-markdown) - Generate
  documentation in Markdown format.
- [jsdoc-md](https://github.com/jaydenseric/jsdoc-md) - Another tool to generate
  documentation in Markdown format.

## Linting

- [eslint-plugin-jsdoc](https://github.com/gajus/eslint-plugin-jsdoc) - JSDoc
  linting rules for ESLint.

## Parsing and Stringifying

- [comment-parser](https://github.com/syavorsky/comment-parser) - JSDoc-*like*
  parsing and stringifying (can also be semantically aware of JSDoc's tags using
  a custom parser like [in eslint-plugin-jsdoc](https://github.com/gajus/eslint-plugin-jsdoc/blob/master/src/iterateJsdoc.js#L28-L85)).
- [jsdoctypeparser](https://github.com/jsdoctypeparser/jsdoctypeparser) - JSDoc
  type parser / stringifier / traverser used in `eslint-plugin-jsdoc` which also
  supports some TypeScript.
- [catharsis](https://github.com/hegemonic/catharsis) - JSDoc type parser used
  within `jsdoc` itself.

## Schema usage

- [json-schema-to-jsdoc](https://github.com/n3ps/json-schema-to-jsdoc) - Convert
  from [JSON Schema](http://json-schema.org/) to JSDoc.
- [jsdoc-jsonschema](https://github.com/brettz9/jsdoc-jsonschema) - Convert
  from JSDoc to [JSON Schema](http://json-schema.org/) (aims to use standard
  `@typedef`).

## Templates

- [better-docs](https://github.com/SoftwareBrothers/better-docs) - A JSDoc 3
  template for your JavaScript and TypeScript projects with support for
  `@category`, `@component`, and `@optional` tags ([example](https://softwarebrothers.github.io/example-design-system/index.html)).
- [Docdash](https://github.com/clenemt/docdash) - A clean, responsive template
  theme for JSDoc 3 ([example](https://clenemt.github.io/docdash/)).
- [DocStrap](https://github.com/docstrap/docstrap) - Bootstrap-based template
  for JSDoc 3 with themes from [Bootswatch](http://bootswatch.com/)
  ([example](https://docstrap.github.io/docstrap/)).
- [jsdoc3Template](https://github.com/DBCDK/jsdoc3Template) - Customizable
  JSDoc 3 template ([screenshots](https://github.com/danyg/jsdoc3Template/wiki#screenshots)).
- [Minami](https://github.com/Nijikokun/minami) - A clean, responsive template
  for JSDoc 3.
- [TUI JSDoc Template](https://github.com/nhn/tui.jsdoc-template) - Toast UI
  JSDoc template.

## Type checking

- [bycontract](https://github.com/dsheiko/bycontract/) - Validate structures
  with JSDoc expressions.
- [eslint-plugin-typelint](https://github.com/yarax/eslint-plugin-typelint) -
  Allow JSON Schema (or Redux reducer) to be pointed to by JSDoc types with
  usage type-checked.
- [tern](https://github.com/ternjs/tern) - Check type usage against JSDoc.

## Visualizations

- [jsdoc2diagram](https://github.com/amcmillan01/jsdoc2diagram) - Create D3
  diagrams from your project's JSDoc.
