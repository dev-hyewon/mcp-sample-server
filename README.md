## MCP 샘플 서버 만들기


> [!note] 환경
> - OS: window11
> - Language: node 22.14.0
 

```shell
node --version
#"v22.14.0" 출력 확인
npm --version
#"10.9.2" 출력 확인
```


```shell
# Create a new directory for our project
md sample-server
cd sample-server

# Initialize a new npm project
npm init -y

# Install dependencies
npm install @modelcontextprotocol/sdk zod
npm install -D @types/node typescript

# Create our files
md src
new-item src\index.ts
```