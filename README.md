<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Faça Cortes e Fique Famoso - Produto Digital</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { background-color: #f8f9fa; font-family: Arial, sans-serif; }
        .hero { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 100px 0; text-align: center; }
        .cta-button { background-color: #28a745; border: none; padding: 15px 30px; font-size: 18px; }
        .cta-button:hover { background-color: #218838; }
        .benefits { padding: 50px 0; }
        .benefit-item { text-align: center; margin-bottom: 30px; }
        .price { font-size: 2em; color: #28a745; font-weight: bold; }
        .preview { padding: 50px 0; background-color: #e9ecef; }
        .preview img { max-width: 100%; height: auto; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2); margin: 20px 0; }
        .testimonials { padding: 50px 0; background-color: #f8f9fa; }
    </style>
</head>
<body>
    <section class="hero">
        <div class="container">
            <h1>Faça Cortes e Fique Famoso</h1>
            <p>Por clips00: Aprenda a editar vídeos curtos e virais que vão te tornar uma estrela nas redes sociais! Guia prático com dicas de cortes, efeitos e estratégias para milhões de visualizações.</p>
            <p class="price">Preço: R$ 10,99</p>
            <button class="cta-button" onclick="window.open('https://nubank.com.br/cobrar/35erh9/697954b1-2076-469e-871b-2537e5757ac1', '_blank')">Comprar Agora via Pix</button>
        </div>
    </section>

    <section class="benefits">
        <div class="container">
            <h2 class="text-center mb-4">Por que escolher este produto?</h2>
            <div class="row">
                <div class="col-md-4 benefit-item">
                    <h4>Edição Profissional</h4>
                    <p>Técnicas simples para cortes que engajam o público e aumentam o alcance.</p>
                </div>
                <div class="col-md-4 benefit-item">
                    <h4>Fama Rápida</h4>
                    <p>Dicas testadas para viralizar seus vídeos no TikTok, Instagram e YouTube.</p>
                </div>
                <div class="col-md-4 benefit-item">
                    <h4>Acesso Imediato</h4>
                    <p>E-book digital: baixe instantaneamente após a compra via Pix.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="preview">
        <div class="container">
            <h2 class="text-center mb-4">Amostra Grátis: Prévia do Ebook</h2>
            <p class="text-center">Veja um gostinho do que você aprenderá! Imagens luxuosas de cortes profissionais para inspirar sua edição.</p>
            <div class="row">
                <div class="col-md-6">
                    <h4>Capítulo 1: Por Que Vídeos Curtos São o Futuro?</h4>
                    <p>Vídeos curtos dominam as redes, com engajamento 3x maior. Aprenda a viralizar com cortes precisos.</p>
                    <img src="https://images.unsplash.com/photo-1611224923853-80b023f02d71?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Cortes luxuosos em vídeo de edição profissional">
                    <p><strong>Dica Rápida:</strong> Use a regra dos 3 segundos para prender a atenção.</p>
                </div>
                <div class="col-md-6">
                    <h4>Técnicas de Cortes Virais</h4>
                    <p>Hook inicial com ação chocante e ritmo dinâmico para milhões de views.</p>
                    <img src="https://images.unsplash.com/photo-1581291518857-4e27b48ff24e?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Efeitos luxuosos de cortes em software de edição">
                    <p><strong>Dica Rápida:</strong> Alterne close-ups e planos gerais para energia alta.</p>
                </div>
            </div>
            <div class="text-center mt-4">
                <p>Gostou? Compre o ebook completo para mais dicas e estratégias!</p>
                <button class="cta-button" onclick="window.open('https://nubank.com.br/cobrar/35erh9/697954b1-2076-469e-871b-2537e5757ac1', '_blank')">Comprar Agora</button>
            </div>
        </div>
    </section>

    <section class="testimonials">
        <div class="container">
            <h2 class="text-center mb-4">O que os usuários dizem</h2>
            <div class="row">
                <div class="col-md-6">
                    <p>"Incrível! Meus vídeos agora têm 10x mais visualizações!" - João S.</p>
                </div>
                <div class="col-md-6">
                    <p>"Dicas práticas e fáceis de aplicar. Recomendo!" - Maria L.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="container my-5">
        <h2 class="text-center">Cadastre-se para Dicas Exclusivas</h2>
        <form id="leadForm">
            <div class="mb-3">
                <input type="email" class="form-control" id="email" placeholder="Seu email" required>
            </div>
            <button type="submit" class="btn btn-primary">Inscrever</button>
        </form>
    </section>

    <footer class="text-center py-4 bg-dark text-white">
        <p>&copy; 2023 clips00. Todos os direitos reservados.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        document.getElementById('leadForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const email = document.getElementById('email').value;
            alert(`Obrigado! ${email} foi cadastrado para receber dicas exclusivas.`);
        });
    </script>
</body>
</html>
