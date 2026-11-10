# aqerke-del.github.io
<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Биоинформатика Құралдары</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff0f5; /* Жұмсақ ақшыл-қызғылт фон */
            color: #4a2e35;            /* Қою күлгін-қызғылт мәтін түсі */
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 4px 15px rgba(216, 27, 96, 0.15);
            border: 2px solid #ffc1e3;
        }
        h1 {
            color: #d81b60;
            text-align: center;
            margin-bottom: 10px;
        }
        .subtitle {
            text-align: center;
            color: #6d4c54;
            margin-bottom: 30px;
        }
        .tool-card {
            background: #fffbfd;
            border: 1px solid #ffc1e3;
            border-radius: 10px;
            padding: 15px 20px;
            margin-bottom: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
        }
        .tool-info {
            flex: 1;
            min-width: 250px;
        }
        .tool-info h3 {
            margin: 0 0 5px 0;
            color: #d81b60;
        }
        .tool-info p {
            margin: 0;
            font-size: 14px;
            color: #555;
        }
        .btn {
            background-color: #d81b60;
            color: white;
            padding: 10px 20px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            font-size: 14px;
            transition: background 0.3s;
            white-space: nowrap;
        }
        .btn:hover {
            background-color: #ad1457;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Биоинформатика Құралдары 🧬</h1>
        <p class="subtitle">ДНҚ, РНҚ және ақуыз тізбектерін салыстыруға арналған негізгі алгоритмдер мен платформалар.</p>

        <!-- EMBOSS Needle -->
        <div class="tool-card">
            <div class="tool-info">
                <h3>EMBOSS Needle</h3>
                <p>Екі тізбекті басынан аяғына дейін толық салыстыруға арналған <strong>жаһандық (Global)</strong> алгоритм.</p>
            </div>
            <a href="https://www.ebi.ac.uk/jdispatcher/psa/emboss_needle" target="_blank" class="btn">Сайтқа өту ➔</a>
        </div>

        <!-- EMBOSS Water -->
        <div class="tool-card">
            <div class="tool-info">
                <h3>EMBOSS Water</h3>
                <p>Тізбектердің ең ұқсас аймақтарын табуға арналған <strong>жергілікті (Local)</strong> Smith-Waterman алгоритмі.</p>
            </div>
            <a href="https://www.ebi.ac.uk/jdispatcher/psa/emboss_water" target="_blank" class="btn">Сайтқа өту ➔</a>
        </div>

        <!-- BLASTn -->
        <div class="tool-card">
            <div class="tool-info">
                <h3>BLASTn</h3>
                <p>Берілген нуклеотидті (ДНҚ/РНҚ) тізбекті NCBI дерекқорындағы басқа тізбектермен салыстырып іздеу.</p>
            </div>
            <a href="https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastn&PAGE_TYPE=BlastSearch" target="_blank" class="btn">Сайтқа өту ➔</a>
        </div>

        <!-- BLASTp -->
        <div class="tool-card">
            <div class="tool-info">
                <h3>BLASTp</h3>
                <p>Ақуыз (протеин) тізбектерін NCBI базасындағы басқа ақуыздармен салыстыру және ұқсастықтарды табу.</p>
            </div>
            <a href="https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastp&PAGE_TYPE=BlastSearch" target="_blank" class="btn">Сайтқа өту ➔</a>
        </div>

    </div>

</body>
</html>
