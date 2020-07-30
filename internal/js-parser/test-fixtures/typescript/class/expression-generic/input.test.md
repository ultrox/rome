# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > expression-generic`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/class/expression-generic/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/class/expression-generic/input.ts"
		end: Object {
			column: 0
			index: 32
			line: 3
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/class/expression-generic/input.ts"
				end: Object {
					column: 14
					index: 14
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSClassExpression {
				id: undefined
				loc: Object {
					filename: "typescript/class/expression-generic/input.ts"
					end: Object {
						column: 12
						index: 12
						line: 1
					}
					start: Object {
						column: 1
						index: 1
						line: 1
					}
				}
				meta: JSClassHead {
					body: Array []
					implements: undefined
					superClass: undefined
					superTypeParameters: undefined
					loc: Object {
						filename: "typescript/class/expression-generic/input.ts"
						end: Object {
							column: 12
							index: 12
							line: 1
						}
						start: Object {
							column: 1
							index: 1
							line: 1
						}
					}
					typeParameters: TSTypeParameterDeclaration {
						loc: Object {
							filename: "typescript/class/expression-generic/input.ts"
							end: Object {
								column: 9
								index: 9
								line: 1
							}
							start: Object {
								column: 6
								index: 6
								line: 1
							}
						}
						params: Array [
							TSTypeParameter {
								name: "T"
								constraint: undefined
								default: undefined
								loc: Object {
									filename: "typescript/class/expression-generic/input.ts"
									end: Object {
										column: 8
										index: 8
										line: 1
									}
									start: Object {
										column: 7
										index: 7
										line: 1
									}
								}
							}
						]
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/class/expression-generic/input.ts"
				end: Object {
					column: 16
					index: 31
					line: 2
				}
				start: Object {
					column: 0
					index: 15
					line: 2
				}
			}
			expression: JSClassExpression {
				id: JSBindingIdentifier {
					name: "C"
					loc: Object {
						filename: "typescript/class/expression-generic/input.ts"
						identifierName: "C"
						end: Object {
							column: 8
							index: 23
							line: 2
						}
						start: Object {
							column: 7
							index: 22
							line: 2
						}
					}
				}
				loc: Object {
					filename: "typescript/class/expression-generic/input.ts"
					end: Object {
						column: 14
						index: 29
						line: 2
					}
					start: Object {
						column: 1
						index: 16
						line: 2
					}
				}
				meta: JSClassHead {
					body: Array []
					implements: undefined
					superClass: undefined
					superTypeParameters: undefined
					loc: Object {
						filename: "typescript/class/expression-generic/input.ts"
						end: Object {
							column: 14
							index: 29
							line: 2
						}
						start: Object {
							column: 1
							index: 16
							line: 2
						}
					}
					typeParameters: TSTypeParameterDeclaration {
						loc: Object {
							filename: "typescript/class/expression-generic/input.ts"
							end: Object {
								column: 11
								index: 26
								line: 2
							}
							start: Object {
								column: 8
								index: 23
								line: 2
							}
						}
						params: Array [
							TSTypeParameter {
								name: "T"
								constraint: undefined
								default: undefined
								loc: Object {
									filename: "typescript/class/expression-generic/input.ts"
									end: Object {
										column: 10
										index: 25
										line: 2
									}
									start: Object {
										column: 9
										index: 24
										line: 2
									}
								}
							}
						]
					}
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