


Ощибка 1
scr/server.ts loc: property.key.loc нет типа loc для property.key 
для json-to-ast.d.ts export interface AstIdentifier добавил loc: AstLocation; 

Ошибка 2

scr/server.ts
conn.onInitialize((params: InitializeParams) => {
    return {
        capabilities: {
            textDocumentSync: 'always'
        }
    };
});

вместо 'always' значение 1