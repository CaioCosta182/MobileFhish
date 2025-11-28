🎣 MobileFish v1.5

Usando a ferramenta MobileFish, você pode gerar diferentes links de phishing para sites de desejos (wishing) ou sites personalizados que podem capturar fotos da câmera frontal da vítima e também fornecer informações de look-up (localização aproximada) do endereço IP do alvo.

🛠️ Correções de Bugs e Novos Recursos Adicionados
Erro de túnel Ngrok corrigido

Sub-Domínio Adicionado

Página de Reunião ao Vivo (Live-Meeting) Adicionada

Página do YouTube ao Vivo Adicionada (Personalizada)

Página de Desejos de Festival Adicionada (Personalizada)

💻 Instalação e Uso

git clone git@github.com:CaioCosta182/FishWish.git
cd WishFish && bash wishfish.sh

Nota: Agora, ligue o ponto de acesso (hotspot) do seu dispositivo antes de usá-lo.

Às vezes, o servidor servero está inativo, então sempre use o ngrok para obter um link instantâneo. Espere até que ele gere o URL e, em seguida, envie-o para a vítima.

⚠️ Nota:
Se a vítima abrir este URL no Chrome ou no navegador nativo do Android, a ferramenta poderá acessar a câmera da vítima solicitando permissões e enviar a foto para você.

As imagens capturadas serão armazenadas na pasta captured. Execute o seguinte script para copiá-las para a pasta pictures:

chmod +x copy.sh && ./copy.sh

Esta informação é apenas para fins educacionais e não sou responsável por qualquer tipo de atividade ilegal realizada com esta ferramenta.
