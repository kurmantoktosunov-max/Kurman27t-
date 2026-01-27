<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Структура студсовета</title>
    <style>
        body {
            font-family: sans-serif;
            background: #f4f4f4;
            margin: 0;
            padding: 40px;
            text-align: center;
        }

        h1 {
            font-size: 28px;
            margin-bottom: 20px;
        }

        .tree {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 30px;
        }

        .row {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

            .row.relative {
                position: relative;
            }

        .president-wrapper {
            position: relative;
            margin-bottom: -20px;
            z-index: 1;
        }

        .section-label {
            font-weight: bold;
            background: #333;
            color: white;
            padding: 6px 12px;
            border-radius: 8px;
            margin-bottom: 10px;
            text-transform: uppercase;
            font-size: 14px;
        }

        .card {
            background: white;
            border: 2px solid #ccc;
            border-radius: 12px;
            padding: 10px;
            width: 160px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }

            .card img {
                width: 100%;
                height: 150px;
                object-fit: cover;
                border-radius: 8px;
            }

            .card h3 {
                margin: 8px 0 4px;
                font-size: 16px;
            }

            .card p {
                margin: 0;
                font-size: 13px;
                color: #555;
            }

            .card a button {
                margin-top: 6px;
                padding: 4px 8px;
                font-size: 12px;
                background: #3498db;
                color: white;
                border: none;
                border-radius: 6px;
                cursor: pointer;
            }

                .card a button:hover {
                    background: #2c80b4;
                }
    </style>
</head>
<body>
    <h1>Структура студенческого совета </h1><div class="tree">
        <!-- Президент на полстроки выше -->  <div class="president-wrapper">
            <div class="section-label">Президент</div>
            <div class="card">
                <img src="./images/sezim.jpg">
                <h3>Sezim</h3>
                <p>Президент</p>
                <a href="./profile/sezim.html"><button>Подробнее</button></a>
            </div>
        </div>  <!-- Вице-президенты -->  <div class="row relative">
            <div>
                <div class="section-label">Вице-президенты</div>
                <div class="row">
                    <div class="card">
                        <img src="./images/kylym.jpg">
                        <h3>Kylym</h3>
                        <p>Вице-президент</p>
                        <a href="./profile/kylym.html"><button>Подробнее</button></a>
                    </div>
                    <div class="card">
                        <img src="./images/adzhar.jpg">
                        <h3>Azhar</h3>
                        <p>Вице-президент</p>
                        <a href="./profile/adzhar.html"><button>Подробнее</button></a>
                    </div>
                </div>
            </div>
        </div>  <!-- HR + PR -->  <div class="row">
            <div>
                <div class="section-label">HR</div>
                <div class="row">
                    <div class="card"><img src="./images/kurman.jpg"><h3>Kurman</h3><p>HR</p><a href="./profile/kurman.html"><button>Подробнее</button></a></div>
                    <div class="card"><img src="./images/aibike.jpg"><h3>Aibiyke</h3><p>HR</p><a href="./profile/aibike.html"><button>Подробнее</button></a></div>
                </div>
            </div>
            <div>
                <div class="section-label">PR</div>
                <div class="row">
                    <div class="card"><img src="./images/aizhan.jpg"><h3>Aizhan</h3><p>PR</p><a href="./profile/aizhan.html"><button>Подробнее</button></a></div>
                    <div class="card"><img src="./images/nurislam.jpg"><h3>Nurislam</h3><p>PR</p><a href="./profile/nurislam.html"><button>Подробнее</button></a></div>
                </div>
            </div>
        </div>  <!-- Event строкой -->  <div>
            <div class="section-label">Event</div>
            <div class="row">
                <div class="card"><img src="./images/aizada.jpg"><h3>Aizada</h3><p>Event</p><a href="./profile/aizada.html"><button>Подробнее</button></a></div>
                <div class="card"><img src="./images/niyas.jpg"><h3>Niyas</h3><p>Event</p><a href="./profile/niyas.html"><button>Подробнее</button></a></div>
                <div class="card"><img src="./images/sandzhardzhan.jpg"><h3>Sandzharzhan</h3><p>Event</p><a href="./profile/sandzhardzhan.html"><button>Подробнее</button></a></div>
                <div class="card"><img src="./images/daniell.jpg"><h3>Daniel</h3><p>Event</p><a href="./profile/daniel.html"><button>Подробнее</button></a></div>
                <div class="card"><img src="./images/bilal.jpg"><h3>Bilal</h3><p>Event</p><a href="./profile/bilal.html"><button>Подробнее</button></a></div>
                <div class="card"><img src="./images/zhyldyz.jpg"><h3>Jyldyz</h3><p>Event</p><a href="./profile/jyldyz.html"><button>Подробнее</button></a></div>
            </div>
        </div>  <!-- Project + IT -->  <div class="row">
            <div>
                <div class="section-label">Project</div>
                <div class="card"><img src="./images/adilet.jpg"><h3>Adilet</h3><p>Project</p><a href="./profile/adilet.html"><button>Подробнее</button></a></div>
            </div>
            <div>
                <div class="section-label">IT</div>
                <div class="card"><img src="./images/as sami.jpg"><h3>As Sami</h3><p>IT</p><a href="./profile/as_sami.html"><button>Подробнее</button></a></div>
            </div>
        </div>
    </div>
</body>
</html>
