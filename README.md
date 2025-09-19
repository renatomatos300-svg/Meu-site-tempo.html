<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🌤️ Previsão do Tempo com Google AdSense</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #74b9ff, #0984e3);
            padding: 20px;
            text-align: center;
            color: #333;
        }
        .container {
            max-width: 500px;
            margin: 40px auto;
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
        }
        input {
            padding: 14px;
            width: 80%;
            max-width: 300px;
            border: 2px solid #ddd;
            border-radius: 30px;
            font-size: 16px;
            margin: 10px 0;
        }
        button {
            padding: 14px 30px;
            background: #00b894;
            color: white;
            border: none;
            border-radius: 30px;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
            margin: 10px 0;
            box-shadow: 0 3px 8px rgba(0,0,0,0.15);
        }
        button:hover {
            background: #009688;
            transform: translateY(-2px);
        }
        #result {
            margin-top: 25px;
            padding: 25px;
            background: #f8f9fa;
            border-radius: 12px;
            min-height: 50px;
            text-align: center;
        }
        .error { color: #e74c3c; font-weight: bold; }
        .success { color: #27ae60; font-weight: bold; }
        footer {
            margin-top: 40px;
            color: white;
            font-size: 0.9rem;
        }
        .ad-container {
            margin: 25px auto;
            padding: 15px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            max-width: 728px;
        }
        .sidebar-ads {
            text-align: center;
            margin: 30px 0;
        }
        .sidebar-ad {
            display: inline-block;
            margin: 0 15px;
            vertical-align: top;
        }
        .adsbygoogle {
            background: #f0f9ff !important;
            border: 2px dashed #3498db !important;
            display: inline-block !important;
            text-align: center;
            line-height: 90px;
            color: #2980b9;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <!-- 📍 BANNER SUPERIOR -->
    <div class="ad-container">
        <ins class="adsbygoogle"
             style="display:inline-block;width:728px;height:90px"
             data-ad-client="ca-pub-7993033578233937"
             data-ad-slot="1919368439"
             data-adtest="on"></ins>
        <script>
             (adsbygoogle = window.adsbygoogle || []).push({});
        </script>
    </div>

    <div class="container">
        <h1>🌤️ Previsão do Tempo</h1>
        <p>Digite o nome da cidade (ex: São Paulo, Rio de Janeiro)</p>
        
        <input type="text" id="city" placeholder="Ex: São Paulo">
        <button onclick="buscarTempo()">Ver Previsão</button>

        <div id="result">
            <p>🔎 Digite uma cidade e clique em "Ver Previsão"</p>
        </div>
    </div>

    <!-- 📍 BANNERS LATERAIS -->
    <div class="sidebar-ads">
        <div class="sidebar-ad">
            <ins class="adsbygoogle"
                 style="display:inline-block;width:300px;height:250px"
                 data-ad-client="ca-pub-7993033578233937"
                 data-ad-slot="1919368439"
                 data-adtest="on"></ins>
            <script>
                 (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
        <div class="sidebar-ad">
            <ins class="adsbygoogle"
                 style="display:inline-bloc
