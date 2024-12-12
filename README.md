Backend:
É necessário executar os seguintes comandos:
  1.composer update
  2. php artisan key:generate
  3. php artisan storage:link(é para aparecer a foto do suap), se fizer esse comando e der erro dizendo que já existe apague a pasta storage dentro de da pasta public e refaça o comando
  4. php artisan migrate
  5. php artisan db:seed --class=GenreSeed
  6. php artisan serve

Front:
Link para o projeto de baixa fidelidade: https://www.figma.com/design/WxsBBksAfdSg8joE0heUws/Baixa-fidelidade?node-id=0-1&node-type=canvas&t=zQafzViQarNryQp4-0
Link para o projeto de média: https://www.figma.com/design/LmOXTSDIAGRy9IwNEIE0zL/GABOOKS?node-id=0-1&node-type=canvas&t=oeKddE0cOTj0YTa6-0
