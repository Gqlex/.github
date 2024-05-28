## Hi there 👋

Using the **gqleX** code library, a developer can easily map out every element in a GraphQL document in relation to the node and context in which it operates, enabling them to:

Identify and select relevant nodes using **gqlXPath**, a syntax similar to Xpath in XML or JSONPath in JSON. The library also provides an equivalent code called SyntaxPath, designed to support automated code selection.
Take advantage of a set of transformer capabilities to add children or sibling nodes, duplicate nodes, remove children nodes, update node names and/or update field aliases.

### Publishing 
https://medium.com/intuit-engineering/simplify-graphql-api-reusability-at-scale-with-extendgql-open-source-library-fb26a9df2e69

https://dev.to/intuitdev/extend-graphql-gxpath-and-enhanced-transformer-12bf

### Support of

Version 1.0
1. Define first version of gqlexpath
2. Path-selection over graphql-lang AST, the ability to select GraphQL.lang.node(s) based on gqlexpath over GraphQL client queries/mutation/etc document.
3. Transform of GraphQL.lang.node(s) on GraphQL client queries/mutation/etc document.

### What Next
1. Support of TLV (Token-Length-Value) for path-selection, new ability in addition to AST based solution.
2. Support of TLV (Token-Length-Value) for transform, new ability in addition to AST based solution.
3. Add filter-predicate to gqlexpath
4. Enhance select-predicate for none-inclusive
5. Propose RFC for graphql foundation

**Feel free to contact us for any issues, questions, insights, comments, or contributions.**
