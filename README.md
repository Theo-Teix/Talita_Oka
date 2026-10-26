# Talita Oka, Nutricionista

Site de página única da nutricionista Talita Oka (CRN3 62151), nutrição esportiva e saúde da mulher, Salto, SP.
HTML, CSS e JavaScript puros, sem build. Todos os botões de agendamento abrem o WhatsApp (11) 97207-8285.

## Estrutura

```
index.html                 página completa (estilos e scripts dentro do arquivo)
img/talita-recorte.webp    foto recortada do topo
img/talita-ecobag.jpg      foto da seção "para quem é"
img/talita-vinho.jpg       foto da seção "sobre"
img/talita-sofa.jpg        foto da chamada final
img/talita-movimento.jpg   foto do treino (Instagram)
img/logo-selo.png          selo original da marca
img/favicon.png            ícone da aba (monograma)
img/apple-touch-icon.png   ícone ao salvar na tela do celular
vercel.json                configuração da Vercel (URLs limpas)
```

## Publicar

1. Crie um repositório no GitHub (ex.: `Talita_Oka`) e envie os arquivos desta pasta para a raiz dele.
   Importante: **arraste a pasta `img` inteira** para a área de upload. O botão "choose your files" não envia pastas.
2. Na Vercel, clique em **Add New → Project**, importe o repositório e mantenha:
   - Project Name: `talita-oka`
   - Framework Preset: **Other**
   - Build Command: vazio
   - Output Directory: vazio (raiz)
3. Clique em **Deploy**. O site fica em https://talita-oka.vercel.app/ e cada novo commit publica a atualização sozinho.

## Imagens

Ao trocar uma imagem mantendo o mesmo nome, aumente o número `?v=1` nos links do `index.html` (por exemplo `?v=2`) para os navegadores baixarem a versão nova.

## Editar conteúdo

- Número do WhatsApp: variável `numero` no fim do `index.html`.
- Mensagens automáticas: atributo `data-wa` de cada botão.
- Cores: variáveis no início do `<style>` (`--musgo`, `--cobre`, `--papel`).
- Se o endereço final do site mudar, atualize `og:url`, `og:image` e `canonical` no `<head>`.
