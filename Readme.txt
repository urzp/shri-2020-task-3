������ 1
scr/server.ts loc: property.key.loc ��� ���� loc ��� property.key 
��� json-to-ast.d.ts export interface AstIdentifier ������� loc: AstLocation; 

������ 2

scr/server.ts
conn.onInitialize((params: InitializeParams) => {
    return {
        capabilities: {
            textDocumentSync: 'always'
        }
    };
});

������ 'always' �������� 1