# Ajay-khatik-
New experiment 
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>स्कैम रक्षक प्रो + अजय करियर कवच</title>
    <!-- Tailwind CSS (Fixed Link) -->
    <script src="https://jsdelivr.net"></script>
    <style>
        @import url('https://googleapis.com');
        body { font-family: 'Noto Sans Devanagari', sans-serif; }
    </style>
</head>
<body class="bg-gradient-to-br from-slate-900 via-indigo-950 to-slate-900 text-slate-100 min-h-screen p-4 flex flex-col items-center">

    <div class="max-w-2xl w-full space-y-6 my-6">
        
        <!-- मुख्य हेडर -->
        <div class="text-center bg-slate-800/60 backdrop-blur-md rounded-2xl p-6 border border-slate-700 shadow-xl">
            <h1 class="text-3xl font-extrabold text-red-500 mb-1 tracking-wide drop-shadow">🛡️ स्कैम रक्षक प्रो</h1>
            <p class="text-sm text-slate-400">अजय खतीक द्वारा समाज की सुरक्षा और भलाई के लिए निर्मित मंच</p>
        </div>

        <!-- टैब नेविगेशन -->
        <div class="flex bg-slate-800 rounded-xl p-1 border border-slate-700">
            <button onclick="switchTab('scam')" id="btn-scam" class="w-1/3 text-center py-2.5 rounded-lg text-sm font-bold bg-red-600 text-white transition-all cursor-pointer">💬 संदेश जाँच</button>
            <button onclick="switchTab('website')" id="btn-website" class="w-1/3 text-center py-2.5 rounded-lg text-sm font-bold text-slate-400 hover:text-slate-200 transition-all cursor-pointer">🌐 वेबसाइट जाँच</button>
            <button onclick="switchTab('kundli')" id="btn-kundli" class="w-1/3 text-center py-2.5 rounded-lg text-sm font-bold text-slate-400 hover:text-slate-200 transition-all cursor-pointer">🕉️ अजय डैशबोर्ड</button>
        </div>

        <!-- टैब 1: संदेश जाँच -->
        <div id="tab-scam" class="bg-slate-800/80 backdrop-blur-md rounded-2xl shadow-xl p-6 border border-slate-700">
            <h2 class="text-lg font-bold text-red-400 mb-4 flex items-center gap-2">💬 संदिग्ध मैसेज की जाँच करें</h2>
            <textarea id="scamText" rows="4" class="w-full p-4 bg-slate-900/60 border border-slate-600 rounded-xl text-sm mb-4 text-white placeholder-slate-500 focus:ring-2 focus:ring-red-500 focus:outline-none" placeholder="यहाँ मैसेज पेस्ट करें... जैसे: 'घर बैठे वीडियो लाइक करके ₹5000 कमाएं'"></textarea>
            <button onclick="analyzeMessage()" class="w-full bg-gradient-to-r from-red-600 to-orange-600 hover:from-red-700 hover:to-orange-700 text-white font-bold py-3 rounded-xl shadow-lg transition active:scale-95 cursor-pointer">स्मार्ट जाँच करें 🔍</button>
            <div id="scamResult" class="hidden mt-4 p-4 rounded-xl text-sm"></div>
        </div>

        <!-- टैब 2: फेक वेबसाइट चेकर -->
        <div id="tab-website" class="hidden bg-slate-800/80 backdrop-blur-md rounded-2xl shadow-xl p-6 border border-slate-700">
            <h2 class="text-lg font-bold text-blue-400 mb-4 flex items-center gap-2">🌐 नकली/फर्जी वेबसाइट की पहचान</h2>
            <input type="text" id="webUrl" class="w-full p-4 bg-slate-900/60 border border-slate-600 rounded-xl text-sm mb-4 text-white placeholder-slate-500 focus:ring-2 focus:ring-blue-500 focus:outline-none" placeholder="वेबसाइट का लिंक डालें (उदा: http://free-laptop-govt.in)">
            <button onclick="analyzeWebsite()" class="w-full bg-gradient-to-r from-blue-600 to-indigo-600 hover:from-blue-700 hover:to-indigo-700 text-white font-bold py-3 rounded-xl shadow-lg transition active:scale-95 cursor-pointer">वेबसाइट की शुद्धता जांचें 🔍</button>
            <div id="webResult" class="hidden mt-4 p-4 rounded-xl text-sm"></div>
        </div>

        <!-- टैब 3: अजय खतीक डैशबोर्ड (पूरा किया गया) -->
        <div id="tab-kundli" class="hidden bg-slate-800/80 backdrop-blur-md rounded-2xl shadow-xl p-6 border border-slate-700 space-y-6">
            <div class="border-b border-slate-700 pb-3">
                <h2 class="text-xl font-bold text-amber-400">🕉️ अजय खतीक - करियर सुरक्षा कवच</h2>
                <p class="text-xs text-slate-400 mt-1">जन्म विवरण: 28 नवंबर 2000 | सायं 5:30 बजे | सुकेत, झालावाड़ (राज.)</p>
            </div>

            <!-- ग्रहों और चक्रों का विश्लेषण -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <div class="bg-slate-900/50 border border-slate-700 p-4 rounded-xl">
                    <h3 class="text-xs font-bold text-indigo-400 mb-2 uppercase tracking-wide">🪐 कुंडली एवं ग्रह प्रभाव</h3>
                    <ul class="text-xs text-slate-300 space-y-2 list-disc pl-4">
                        <li><strong>लग्न/राशि:</strong> वृषभ लग्न, धनु राशि। मेहनत और साहस का उत्तम मेल।</li>
                        <li><strong>राहु का प्रभाव:</strong> वर्तमान में 30-35% तामसिक ऊर्जा के कारण थोड़ा भ्रम और आलस है, जो मई 2027 तक पूरी तरह नष्ट हो जाएगा।</li>
                        <li><strong>शुभ समय (शुद्धिकरण):</strong> फरवरी 2027 से मई 2027 के बीच बड़ा बदलाव होगा।</li>
                    </ul>
                </div>
                
                <div class="bg-slate-900/50 border border-slate-700 p-4 rounded-xl">
                    <h3 class="text-xs font-bold text-emerald-400 mb-2 uppercase tracking-wide">⚡ मुख्य चक्रों की शक्ति</h3>
                    <ul class="text-xs text-slate-300 space-y-2 list-disc pl-4">
                        <li><strong>आज्ञा चक्र (90%):</strong> अत्यधिक सक्रिय, तीव्र अंतःप्रेरणा (Intuition)।</li>
                        <li><strong>अनाहत चक्र (85%):</strong> माता-पिता के प्रति गहरी भक्ति व प्रेम।</li>
                        <li><strong>मूलाधार चक्र (35%):</strong> करियर की चिंता के कारण अस्थिरता, जिसे कर्म पथ से मजबूत करना है।</li>
                    </ul>
                </div>
            </div>

            <div class="bg-indigo-950/40 border border-indigo-800/60 p-4 rounded-xl text-center">
                <p class="text-sm font-bold text-indigo-300">🎯 भविष्य का मंत्र</p>
                <p class="text-xs text-slate-300 mt-1">"ऑफिस बॉय की नौकरी + फ्रीलांसिंग (Upwork/LinkedIn) = शिव-शक्ति का आशीर्वाद और पहली स्वतंत्र कमाई से राहु का भ्रम नष्ट होगा।"</p>
            </div>
        </div>

    </div>

    <!-- स्मार्ट लॉजिक स्क्रिप्ट -->
    <script>
        function switchTab(tabName) {
            // सभी टैब छुपाएं
            document.getElementById('tab-scam').classList.add('hidden');
            document.getElementById('tab-website').classList.add('hidden');
            document.getElementById('tab-kundli').classList.add('hidden');
            
            // सभी बटन का स्टाइल रीसेट करें
            document.getElementById('btn-scam').className = "w-1/3 text-center py-2.5 rounded-lg text-sm font-bold text-slate-400 hover:text-slate-200 transition-all cursor-pointer";
            document.getElementById('btn-website').className = "w-1/3 text-center py-2.5 rounded-lg text-sm font-bold text-slate-400 hover:text-slate-200 transition-all cursor-pointer";
            document.getElementById('btn-kundli').className = "w-1/3 text-center py-2.5 rounded-lg text-sm font-bold text-slate-400 hover:text-slate-200 transition-all cursor-pointer";

            // चुने गए टैब को दिखाएं और बटन को एक्टिव करें
            if(tabName === 'scam') {
                document.getElementById('tab-scam').classList.remove('hidden');
                document.getElementById('btn-scam').className = "w-1/3 text-center py-2.5 rounded-lg text-sm font-bold bg-red-600 text-white transition-all cursor-pointer";
            } else if(tabName === 'website') {
                document.getElementById('tab-website').classList.remove('hidden');
                document.getElementById('btn-website').className = "w-1/3 text-center py-2.5 rounded-lg text-sm font-bold bg-blue-600 text-white transition-all cursor-pointer";
            } else if(tabName === 'kundli') {
                document.getElementById('tab-kundli').classList.remove('hidden');
                document.getElementById('btn-kundli').className = "w-1/3 text-center py-2.5 rounded-lg text-sm font-bold bg-amber-600 text-white transition-all cursor-pointer";
            }
        }

        function analyzeMessage() {
            const text = document.getElementById('scamText').value.trim();
            const resultDiv = document.getElementById('scamResult');
            
            if(!text) {
                alert("कृपया कोई मैसेज दर्ज करें!");
                return;
            }

            resultDiv.classList.remove('hidden');
            // स्कैम कीवर्ड्स की जांच
            if(text.includes('कमाएं') || text.includes('लाइक') || text.includes('जीतें') || text.includes('फ्री') || text.includes('₹')) {
                resultDiv.className = "mt-4 p-4 rounded-xl text-sm bg-red-950/50 border border-red-800 text-red-300";
                resultDiv.innerHTML = "🚨 <strong>चेतावनी:</strong> यह संदेश 99% स्कैम (धोखाधड़ी) हो सकता है! इसमें बिना मेहनत के पैसे कमाने या लालच देने वाले शब्द हैं। कृपया कोई व्यक्तिगत जानकारी या ओटीपी शेयर न करें।";
            } else {
                resultDiv.className = "mt-4 p-4 rounded-xl text-sm bg-emerald-950/50 border border-emerald-800 text-emerald-300";
                resultDiv.innerHTML = "✅ <strong>सुरक्षित प्रतीत होता है:</strong> इस संदेश में कोई सामान्य स्कैम कीवर्ड नहीं मिला। फिर भी सतर्क रहें!";
            }
        }

        function analyzeWebsite() {
            const url = document.getElementById('webUrl').value.trim().toLowerCase();
            const resultDiv = document.getElementById('webResult');

            if(!url) {
                alert("कृपया वेबसाइट का लिंक डालें!");
                return;
            }

            resultDiv.classList.remove('hidden');
            
            // फेक डोमेन की बुनियादी जांच
            if(url.includes('.in.net') ||