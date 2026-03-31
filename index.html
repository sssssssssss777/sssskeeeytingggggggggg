<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>Скейтинг система</title>
    <style>
        * {
            box-sizing: border-box;
        }
        body {
            background: #e8f3ec;
            font-family: 'Segoe UI', 'Roboto', system-ui, sans-serif;
            margin: 0;
            padding: 24px 20px;
            color: #1a3a2a;
        }
        .app-card {
            max-width: 100%;
            background: white;
            border-radius: 32px;
            box-shadow: 0 12px 28px rgba(0, 40, 0, 0.1);
            padding: 20px 20px 28px;
        }
        h1 {
            margin: 0 0 16px 0;
            font-size: 2rem;
            font-weight: 700;
            color: #1c6e3c;
        }
        .controls {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin: 0 0 20px 0;
            background: #f6fef8;
            padding: 14px 20px;
            border-radius: 48px;
            align-items: flex-end;
            border: 1px solid #bde0c6;
        }
        .ctrl-group {
            display: flex;
            flex-direction: column;
            gap: 6px;
        }
        .ctrl-group label {
            font-size: 0.75rem;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.6px;
            color: #2b7846;
        }
        input {
            background: white;
            border: 1px solid #b9dbc6;
            padding: 8px 14px;
            border-radius: 44px;
            color: #1c4d2d;
            font-weight: 600;
            font-size: 1rem;
            width: 100px;
            text-align: center;
            outline: none;
        }
        input:focus {
            border-color: #2a9d52;
            box-shadow: 0 0 0 3px rgba(60, 173, 98, 0.25);
        }
        button {
            background: #2a9d52;
            border: none;
            padding: 8px 26px;
            border-radius: 48px;
            font-weight: 700;
            font-size: 0.9rem;
            color: white;
            cursor: pointer;
            transition: 0.08s linear;
        }
        button:active {
            transform: scale(0.96);
            background: #1f7c42;
        }
        .table-container {
            overflow-x: auto;
            border-radius: 24px;
            border: 1px solid #c8e0d0;
            background: white;
            margin-bottom: 24px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 14px;
            background: white;
            min-width: 500px;
        }
        th {
            background: #eef7f1;
            color: #1c603a;
            padding: 14px 8px;
            font-weight: 700;
            border-bottom: 2px solid #bcddca;
            border-right: 1px solid #d2e9db;
            text-align: center;
        }
        td {
            border: 1px solid #d8ecdf;
            padding: 8px;
            text-align: center;
            vertical-align: middle;
        }
        .couple-label {
            background: #eef7f1;
            font-weight: 600;
            white-space: nowrap;
        }
        .judge-input {
            width: 70px;
            background: white;
            border: 1px solid #c2dfce;
            padding: 10px 4px;
            text-align: center;
            font-size: 1rem;
            font-weight: 500;
            border-radius: 40px;
            transition: 0.05s linear;
        }
        .judge-input:focus {
            background: #fafff7;
            border-color: #2a9d52;
            outline: none;
            box-shadow: 0 0 0 2px #a2dfb8;
        }
        .judge-input.invalid {
            border-color: #e07c4c;
            background: #fff2e6;
        }
        .dance-tab {
            display: flex;
            gap: 8px;
            margin-bottom: 16px;
            flex-wrap: wrap;
        }
        .dance-btn {
            background: #c8e6d4;
            color: #1c5a36;
            padding: 8px 20px;
            border-radius: 40px;
            font-weight: 600;
            cursor: pointer;
            transition: 0.1s;
        }
        .dance-btn.active {
            background: #2a9d52;
            color: white;
            box-shadow: 0 2px 6px rgba(0,0,0,0.2);
        }
        .dance-btn:hover {
            background: #9fcfb2;
        }
        .final-results {
            background: #f0f9f2;
            border-radius: 24px;
            padding: 16px 20px;
            border: 1px solid #c8e0d0;
        }
        .final-title {
            font-weight: 700;
            font-size: 1.1rem;
            color: #1c6e3c;
            margin-bottom: 12px;
        }
        .final-column {
            display: flex;
            flex-direction: column;
            gap: 8px;
        }
        .final-row {
            display: flex;
            align-items: baseline;
            gap: 16px;
            padding: 6px 0;
            border-bottom: 1px solid #d4ecdd;
        }
        .final-place-num {
            font-weight: 800;
            font-size: 1rem;
            color: #1c6e3c;
            min-width: 60px;
        }
        .final-couples-list {
            color: #2a5a3a;
            font-weight: 500;
        }
        .status {
            margin-top: 12px;
            font-size: 0.75rem;
            color: #3b7853;
            text-align: center;
        }
    </style>
</head>
<body>
<div class="app-card">
    <h1>СКЕЙТИНГ СИСТЕМА</h1>

    <div class="controls">
        <div class="ctrl-group">
            <label>СУДЕЙ</label>
            <input type="number" id="judgesNum" min="3" max="30" value="5" step="1">
        </div>
        <div class="ctrl-group">
            <label>ПАР</label>
            <input type="number" id="couplesNum" min="2" max="30" value="6" step="1">
        </div>
        <div class="ctrl-group">
            <label>ТАНЦЕВ</label>
            <input type="number" id="dancesNum" min="1" max="12" value="4" step="1">
        </div>
        <button id="rebuildBtn">СОЗДАТЬ</button>
        <button id="calculateBtn">РАССЧИТАТЬ МЕСТА</button>
    </div>

    <div class="dance-tab" id="danceTabs"></div>
    
    <div class="table-container">
        <table id="skatingTable">
            <thead id="tableHead"></thead>
            <tbody id="tableBody"></tbody>
        </table>
    </div>
    
    <div class="final-results" id="finalResultsBlock" style="display: none;">
        <div class="final-title">ИТОГОВЫЕ МЕСТА</div>
        <div class="final-column" id="finalColumn"></div>
    </div>
    <div class="status" id="infoStatus"></div>
</div>

<script>
    // Глобальные переменные
    let judges = 5, couples = 6, dances = 4;
    let currentDance = 0;
    let allData = []; // allData[dance][couple][judge] = место (int)
    let inputElements = []; // [dance][couple][judge] -> DOM input
    let danceButtons = [];
    
    // Получение элементов DOM
    const judgesInput = document.getElementById('judgesNum');
    const couplesInput = document.getElementById('couplesNum');
    const dancesInput = document.getElementById('dancesNum');
    const rebuildBtn = document.getElementById('rebuildBtn');
    const calculateBtn = document.getElementById('calculateBtn');
    const tableHead = document.getElementById('tableHead');
    const tableBody = document.getElementById('tableBody');
    const danceTabsDiv = document.getElementById('danceTabs');
    const infoStatus = document.getElementById('infoStatus');
    const finalResultsBlock = document.getElementById('finalResultsBlock');
    const finalColumn = document.getElementById('finalColumn');
    
    // Проверка уникальности мест для текущего танца (правило 4)
    function validateUniquePlacesInDance(danceIdx) {
        if (!allData[danceIdx]) return true;
        for (let j = 0; j < judges; j++) {
            const placesForJudge = [];
            for (let c = 0; c < couples; c++) {
                const val = allData[danceIdx][c][j];
                if (val !== null && val !== undefined && val >= 1 && val <= couples) {
                    placesForJudge.push(val);
                }
            }
            const uniquePlaces = new Set(placesForJudge);
            if (placesForJudge.length === couples && uniquePlaces.size !== couples) {
                for (let c = 0; c < couples; c++) {
                    const inp = inputElements[danceIdx]?.[c]?.[j];
                    if (inp) inp.classList.add('invalid');
                }
            } else {
                for (let c = 0; c < couples; c++) {
                    const inp = inputElements[danceIdx]?.[c]?.[j];
                    if (inp) inp.classList.remove('invalid');
                }
            }
        }
        return true;
    }
    
    // Переключение танца
    function switchToDance(danceIdx) {
        currentDance = danceIdx;
        danceButtons.forEach((btn, idx) => {
            if (idx === danceIdx) btn.classList.add('active');
            else btn.classList.remove('active');
        });
        renderTableForDance();
        setTimeout(() => focusFirstEmptyInCurrentDance(), 30);
    }
    
    function renderTableForDance() {
        tableHead.innerHTML = '';
        tableBody.innerHTML = '';
        if (!allData[currentDance]) return;
        
        // заголовок: "ПАРЫ" и номера судей с подписью "Судья"
        const headerRow = document.createElement('tr');
        const thCorner = document.createElement('th');
        thCorner.innerText = 'ПАРЫ';
        thCorner.style.minWidth = '90px';
        headerRow.appendChild(thCorner);
        for (let j = 0; j < judges; j++) {
            const th = document.createElement('th');
            th.innerText = `Судья ${j+1}`;
            th.style.fontSize = '0.9rem';
            headerRow.appendChild(th);
        }
        tableHead.appendChild(headerRow);
        
        // строки для каждой пары с подписью "1 пара", "2 пара" и т.д.
        for (let c = 0; c < couples; c++) {
            const tr = document.createElement('tr');
            const tdLabel = document.createElement('td');
            tdLabel.innerText = `${c+1} пара`;
            tdLabel.className = 'couple-label';
            tdLabel.style.fontWeight = 'bold';
            tr.appendChild(tdLabel);
            
            for (let j = 0; j < judges; j++) {
                const td = document.createElement('td');
                const inp = inputElements[currentDance][c][j];
                if (inp) {
                    td.appendChild(inp);
                } else {
                    const newInp = document.createElement('input');
                    newInp.type = 'number';
                    newInp.min = 1;
                    newInp.max = couples;
                    newInp.placeholder = '•';
                    newInp.className = 'judge-input';
                    newInp.dataset.dance = currentDance;
                    newInp.dataset.couple = c;
                    newInp.dataset.judge = j;
                    newInp.value = allData[currentDance][c][j] !== null ? allData[currentDance][c][j] : '';
                    newInp.addEventListener('input', handleInputMove);
                    newInp.addEventListener('blur', () => validateUniquePlacesInDance(currentDance));
                    inputElements[currentDance][c][j] = newInp;
                    td.appendChild(newInp);
                }
                tr.appendChild(td);
            }
            tableBody.appendChild(tr);
        }
        
        validateUniquePlacesInDance(currentDance);
    }
    
    function focusFirstEmptyInCurrentDance() {
        for (let c = 0; c < couples; c++) {
            for (let j = 0; j < judges; j++) {
                const inp = inputElements[currentDance]?.[c]?.[j];
                if (inp && (inp.value === '' || inp.value === null)) {
                    inp.focus();
                    return;
                }
            }
        }
        const firstInp = inputElements[currentDance]?.[0]?.[0];
        if (firstInp) firstInp.focus();
    }
    
    // Автопереход
    function handleInputMove(e) {
        const inp = e.target;
        let raw = inp.value.trim();
        if (raw === '') return;
        let val = parseInt(raw);
        if (isNaN(val)) {
            inp.value = '';
            return;
        }
        val = Math.min(couples, Math.max(1, val));
        inp.value = val;
        
        const dance = parseInt(inp.dataset.dance);
        const couple = parseInt(inp.dataset.couple);
        const judge = parseInt(inp.dataset.judge);
        
        if (!allData[dance]) allData[dance] = [];
        if (!allData[dance][couple]) allData[dance][couple] = [];
        allData[dance][couple][judge] = val;
        
        // проверка уникальности
        const placesForJudge = [];
        for (let c = 0; c < couples; c++) {
            const p = allData[dance][c][judge];
            if (p !== null && p !== undefined) placesForJudge.push(p);
        }
        const uniqueSet = new Set(placesForJudge);
        if (placesForJudge.length === couples && uniqueSet.size !== couples) {
            for (let c = 0; c < couples; c++) {
                const cell = inputElements[dance][c][judge];
                if (cell) cell.classList.add('invalid');
            }
            infoStatus.innerText = `⚠️ Судья ${judge+1}: места не должны повторяться`;
        } else {
            for (let c = 0; c < couples; c++) {
                const cell = inputElements[dance][c][judge];
                if (cell) cell.classList.remove('invalid');
            }
            infoStatus.innerText = '';
        }
        
        // переход: следующая пара
        let nextDance = dance;
        let nextJudge = judge;
        let nextCouple = couple + 1;
        
        if (nextCouple >= couples) {
            nextCouple = 0;
            nextJudge = judge + 1;
            if (nextJudge >= judges) {
                nextJudge = 0;
                nextDance = dance + 1;
                if (nextDance >= dances) {
                    calculateAndDisplayResults();
                    return;
                } else {
                    switchToDance(nextDance);
                    return;
                }
            }
        }
        
        if (inputElements[nextDance] && inputElements[nextDance][nextCouple] && inputElements[nextDance][nextCouple][nextJudge]) {
            const nextInput = inputElements[nextDance][nextCouple][nextJudge];
            nextInput.focus();
            nextInput.select();
        }
    }
    
    // ------------------- ЯДРО ПРАВИЛ 5-11 -------------------------
    function getDancePlaces(danceIdx) {
        const nJudges = judges;
        const nCouples = couples;
        const couplePlaces = Array(nCouples).fill().map(() => Array(nJudges).fill(0));
        for (let c = 0; c < nCouples; c++) {
            for (let j = 0; j < nJudges; j++) {
                let p = allData[danceIdx]?.[c]?.[j];
                if (p === undefined || p === null || isNaN(p)) p = nCouples;
                p = Math.min(nCouples, Math.max(1, p));
                couplePlaces[c][j] = p;
            }
        }
        const neededMajority = Math.floor(nJudges / 2) + 1;
        const assigned = Array(nCouples).fill(false);
        const result = Array(nCouples).fill(null);
        let nextPlace = 1;
        
        while (nextPlace <= nCouples) {
            let candidates = [];
            for (let c = 0; c < nCouples; c++) {
                if (assigned[c]) continue;
                const votes = couplePlaces[c];
                for (let k = 1; k <= nCouples; k++) {
                    const cnt = votes.filter(v => v <= k).length;
                    if (cnt >= neededMajority) {
                        const sum = votes.filter(v => v <= k).reduce((a,b)=>a+b,0);
                        candidates.push({ idx: c, threshold: k, count: cnt, sum: sum });
                        break;
                    }
                }
            }
            if (candidates.length === 0) {
                const remaining = [];
                for (let i=0;i<nCouples;i++) if(!assigned[i]) remaining.push(i);
                const avgPlace = (nextPlace + (nextPlace + remaining.length - 1)) / remaining.length;
                for (let r of remaining) result[r] = avgPlace;
                break;
            }
            candidates.sort((a,b) => {
                if (a.threshold !== b.threshold) return a.threshold - b.threshold;
                if (a.count !== b.count) return b.count - a.count;
                if (a.sum !== b.sum) return a.sum - b.sum;
                return 0;
            });
            const best = candidates[0];
            result[best.idx] = nextPlace;
            assigned[best.idx] = true;
            nextPlace++;
        }
        for (let i=0;i<nCouples;i++) if (result[i] === null) result[i] = nextPlace++;
        return result;
    }
    
    function compareByRule10and11(a, b, dancePlacesMatrix, fullJudgeData) {
        const nDances = dances;
        const placesA = dancePlacesMatrix.map(d => d[a]);
        const placesB = dancePlacesMatrix.map(d => d[b]);
        
        for (let k = 1; k <= couples; k++) {
            const cntA = placesA.filter(p => p <= k).length;
            const cntB = placesB.filter(p => p <= k).length;
            if (cntA !== cntB) return cntA > cntB ? -1 : 1;
            if (cntA > 0) {
                const sumA = placesA.filter(p => p <= k).reduce((s,v)=>s+v,0);
                const sumB = placesB.filter(p => p <= k).reduce((s,v)=>s+v,0);
                if (sumA !== sumB) return sumA < sumB ? -1 : 1;
            }
        }
        // правило 11: большой скейтинг
        const totalCells = judges * dances;
        const neededMajority = Math.floor(totalCells / 2) + 1;
        let votesA = [], votesB = [];
        for (let d = 0; d < dances; d++) {
            for (let j = 0; j < judges; j++) {
                let pa = fullJudgeData[d]?.[a]?.[j];
                let pb = fullJudgeData[d]?.[b]?.[j];
                if (pa === undefined || pa === null) pa = couples;
                if (pb === undefined || pb === null) pb = couples;
                votesA.push(pa);
                votesB.push(pb);
            }
        }
        for (let thr = 1; thr <= couples; thr++) {
            const cntA = votesA.filter(v => v <= thr).length;
            const cntB = votesB.filter(v => v <= thr).length;
            if (cntA !== cntB) return cntA > cntB ? -1 : 1;
            if (cntA >= neededMajority) {
                const sumA = votesA.filter(v => v <= thr).reduce((s,x)=>s+x,0);
                const sumB = votesB.filter(v => v <= thr).reduce((s,x)=>s+x,0);
                if (sumA !== sumB) return sumA < sumB ? -1 : 1;
            }
        }
        return 0;
    }
    
    function calculateAndDisplayResults() {
        // получаем места в каждом танце
        const dancePlaces = [];
        for (let d = 0; d < dances; d++) {
            dancePlaces.push(getDancePlaces(d));
        }
        // сумма мест (правило 9)
        const totalSums = Array(couples).fill(0);
        for (let c = 0; c < couples; c++) {
            let sum = 0;
            for (let d = 0; d < dances; d++) {
                sum += dancePlaces[d][c];
            }
            totalSums[c] = sum;
        }
        // сортировка с разрешением ничьих
        let indices = Array.from({length: couples}, (_,i) => i);
        indices.sort((a,b) => {
            if (totalSums[a] !== totalSums[b]) return totalSums[a] - totalSums[b];
            return compareByRule10and11(a, b, dancePlaces, allData);
        });
        
        const finalPlaces = Array(couples).fill(0);
        let currentRank = 1;
        for (let i = 0; i < indices.length; i++) {
            if (i > 0) {
                const prev = indices[i-1];
                const curr = indices[i];
                const sameSum = Math.abs(totalSums[prev] - totalSums[curr]) < 1e-6;
                const cmp = sameSum ? compareByRule10and11(prev, curr, dancePlaces, allData) : 1;
                if (sameSum && cmp === 0) {
                    finalPlaces[curr] = finalPlaces[prev];
                } else {
                    finalPlaces[curr] = currentRank;
                }
            } else {
                finalPlaces[indices[i]] = currentRank;
            }
            currentRank++;
        }
        // выравнивание мест (устраняем пропуски)
        const sortedByFinal = [...Array(couples).keys()].sort((a,b)=>finalPlaces[a]-finalPlaces[b]);
        let rank = 1;
        for (let i=0;i<sortedByFinal.length;i++) {
            const cid = sortedByFinal[i];
            if (i===0) finalPlaces[cid] = rank;
            else {
                if (Math.abs(finalPlaces[cid] - finalPlaces[sortedByFinal[i-1]]) > 1e-6) rank = i+1;
                finalPlaces[cid] = rank;
            }
        }
        
        // формируем список мест от 1 до максимума с перечислением пар
        const maxPlace = Math.max(...finalPlaces);
        const placeToCouples = {};
        for (let c = 0; c < couples; c++) {
            const place = finalPlaces[c];
            if (!placeToCouples[place]) placeToCouples[place] = [];
            placeToCouples[place].push(c + 1);
        }
        
        // отображаем итоговые места в виде колонки: место и список пар
        finalColumn.innerHTML = '';
        for (let p = 1; p <= maxPlace; p++) {
            if (placeToCouples[p] && placeToCouples[p].length > 0) {
                const row = document.createElement('div');
                row.className = 'final-row';
                const placeSpan = document.createElement('div');
                placeSpan.className = 'final-place-num';
                placeSpan.innerText = `${p} место`;
                const couplesSpan = document.createElement('div');
                couplesSpan.className = 'final-couples-list';
                const couplesText = placeToCouples[p].map(num => `${num} пара`).join(', ');
                couplesSpan.innerText = couplesText;
                row.appendChild(placeSpan);
                row.appendChild(couplesSpan);
                finalColumn.appendChild(row);
            }
        }
        
        finalResultsBlock.style.display = 'block';
        infoStatus.innerText = '';
    }
    
    // Перестроение всей таблицы
    function rebuildFull() {
        judges = Math.min(30, Math.max(3, parseInt(judgesInput.value) || 5));
        couples = Math.min(30, Math.max(2, parseInt(couplesInput.value) || 6));
        dances = Math.min(12, Math.max(1, parseInt(dancesInput.value) || 4));
        judgesInput.value = judges;
        couplesInput.value = couples;
        dancesInput.value = dances;
        
        allData = Array(dances).fill().map(() => Array(couples).fill().map(() => Array(judges).fill(null)));
        inputElements = Array(dances).fill().map(() => Array(couples).fill().map(() => Array(judges).fill(null)));
        
        danceTabsDiv.innerHTML = '';
        danceButtons = [];
        for (let d = 0; d < dances; d++) {
            const btn = document.createElement('div');
            btn.className = 'dance-btn';
            btn.innerText = `Танец ${d+1}`;
            btn.addEventListener('click', () => switchToDance(d));
            danceTabsDiv.appendChild(btn);
            danceButtons.push(btn);
        }
        
        currentDance = 0;
        if (danceButtons.length) danceButtons[0].classList.add('active');
        finalResultsBlock.style.display = 'none';
        renderTableForDance();
        infoStatus.innerText = '';
    }
    
    rebuildBtn.addEventListener('click', rebuildFull);
    calculateBtn.addEventListener('click', () => calculateAndDisplayResults());
    
    rebuildFull();
</script>
</body>
</html>
