# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-template-literals > tagged`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-template-literals/tagged/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-template-literals/tagged/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-template-literals/tagged/input.js"
				end: Object {
					column: 7
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSTaggedTemplateExpression {
				typeArguments: undefined
				loc: Object {
					filename: "esprima/es2015-template-literals/tagged/input.js"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				tag: JSReferenceIdentifier {
					name: "raw"
					loc: Object {
						filename: "esprima/es2015-template-literals/tagged/input.js"
						identifierName: "raw"
						end: Object {
							column: 3
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
				}
				quasi: JSTemplateLiteral {
					expressions: Array []
					loc: Object {
						filename: "esprima/es2015-template-literals/tagged/input.js"
						end: Object {
							column: 7
							line: 1
						}
						start: Object {
							column: 3
							line: 1
						}
					}
					quasis: Array [
						JSTemplateElement {
							cooked: "42"
							raw: "42"
							tail: true
							loc: Object {
								filename: "esprima/es2015-template-literals/tagged/input.js"
								end: Object {
									column: 6
									line: 1
								}
								start: Object {
									column: 4
									line: 1
								}
							}
						}
					]
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
