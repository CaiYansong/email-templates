# email-templates

编译单个文件：
npx mjml mjml/test.mjml -o build/test.html

编译多个文件：
npx mjml mjml/*.mjml -o build/

编译文件并实时更新至output.html (需要使用服务器打开:http://127.0.0.1:5500/test.html )
npx mjml -w test.mjml -o test.html
