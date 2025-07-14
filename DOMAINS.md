# Geramos uma aplicação utilizando o V0 da Vercel:

Realizamos o deploy dela com a configuração padrão do NextJS:

Sem Edge:
https://front-end-na-edge-gufers-sample-no.vercel.app/
https://github.com/csfeijo/front-end-na-edge-gufers-sample-no-edge
x-vercel-id: gru1::d66h7-1752500996191-8a1b7bdf735b

Criamos uma nova aplicação identica e adicionamos as configurações para executar usando a Edge:

Com edge:
https://v0-edge-computing-webpage.vercel.app/
https://github.com/csfeijo/front-end-na-edge-gufers-sample

x-vercel-id: gru1::gru1::zwc7g-1752500168579-f0223e9920fc


# Falar sobre as métricas de web-vitals rapidamente
E focar no TTFB.


# Mostrar os números do TTFB (via Network / Timing)

Será que conseguimos mostrar algo relacionado ao deploy em um servidor tradicional?

Roda ```pnpm run build``` na branch deploy-tradicional, depois um ```pnpm dlx serve out``` para executar preview.

Depois faz upload via FTP para o diretório.


