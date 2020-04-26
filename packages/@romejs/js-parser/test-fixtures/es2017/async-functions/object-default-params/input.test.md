# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > object-default-params`

```javascript
Program {
  comments: Array []
  corrupt: true
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 38
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        advice: Array []
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unexpected token, expected ,'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 23
          index: 23
          line: 1
        }
        start: Object {
          column: 22
          index: 22
          line: 1
        }
      }
    }
  ]
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 29
          index: 29
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'const'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 29
            index: 29
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'b'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 7
                  index: 7
                  line: 1
                }
                start: Object {
                  column: 6
                  index: 6
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 29
                index: 29
                line: 1
              }
              start: Object {
                column: 6
                index: 6
                line: 1
              }
            }
            init: CallExpression {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 29
                  index: 29
                  line: 1
                }
                start: Object {
                  column: 10
                  index: 10
                  line: 1
                }
              }
              callee: ReferenceIdentifier {
                name: 'async'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 15
                    index: 15
                    line: 1
                  }
                  start: Object {
                    column: 10
                    index: 10
                    line: 1
                  }
                }
              }
              arguments: Array [
                AssignmentExpression {
                  operator: '='
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 29
                      index: 29
                      line: 1
                    }
                    start: Object {
                      column: 17
                      index: 17
                      line: 1
                    }
                  }
                  right: StringLiteral {
                    value: 'bar'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 29
                        index: 29
                        line: 1
                      }
                      start: Object {
                        column: 24
                        index: 24
                        line: 1
                      }
                    }
                  }
                  left: AssignmentObjectPattern {
                    rest: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 21
                        index: 21
                        line: 1
                      }
                      start: Object {
                        column: 17
                        index: 17
                        line: 1
                      }
                    }
                    properties: Array [
                      AssignmentObjectPatternProperty {
                        key: StaticPropertyKey {
                          value: Identifier {
                            name: 'bar'
                            loc: Object {
                              filename: 'input.js'
                              end: Object {
                                column: 21
                                index: 21
                                line: 1
                              }
                              start: Object {
                                column: 18
                                index: 18
                                line: 1
                              }
                            }
                          }
                          variance: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 21
                              index: 21
                              line: 1
                            }
                            start: Object {
                              column: 18
                              index: 18
                              line: 1
                            }
                          }
                        }
                        value: AssignmentIdentifier {
                          name: 'bar'
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 21
                              index: 21
                              line: 1
                            }
                            start: Object {
                              column: 18
                              index: 18
                              line: 1
                            }
                          }
                        }
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 21
                            index: 21
                            line: 1
                          }
                          start: Object {
                            column: 18
                            index: 18
                            line: 1
                          }
                        }
                      }
                    ]
                  }
                }
              ]
            }
          }
        ]
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 30
          index: 30
          line: 1
        }
        start: Object {
          column: 29
          index: 29
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: 'INVALID_PLACEHOLDER'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 30
            index: 30
            line: 1
          }
          start: Object {
            column: 29
            index: 29
            line: 1
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 31
          index: 31
          line: 1
        }
        start: Object {
          column: 30
          index: 30
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: 'INVALID_PLACEHOLDER'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 31
            index: 31
            line: 1
          }
          start: Object {
            column: 30
            index: 30
            line: 1
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 34
          index: 34
          line: 1
        }
        start: Object {
          column: 32
          index: 32
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: 'INVALID_PLACEHOLDER'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 34
            index: 34
            line: 1
          }
          start: Object {
            column: 32
            index: 32
            line: 1
          }
        }
      }
    }
    BlockStatement {
      body: Array []
      directives: Array []
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 37
          index: 37
          line: 1
        }
        start: Object {
          column: 35
          index: 35
          line: 1
        }
      }
    }
  ]
}
```