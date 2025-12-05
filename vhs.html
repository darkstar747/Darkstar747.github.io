<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>V-HS Progress Tracker</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
        }
        
        h1 {
            color: #667eea;
            margin-bottom: 10px;
            font-size: 2.5em;
        }
        
        .subtitle {
            color: #666;
            margin-bottom: 30px;
            font-size: 1.1em;
        }
        
        .tabs {
            display: flex;
            gap: 10px;
            margin-bottom: 30px;
            border-bottom: 2px solid #e0e0e0;
        }
        
        .tab {
            padding: 15px 25px;
            background: none;
            border: none;
            font-size: 1.1em;
            cursor: pointer;
            color: #666;
            border-bottom: 3px solid transparent;
            transition: all 0.3s;
        }
        
        .tab.active {
            color: #667eea;
            border-bottom-color: #667eea;
            font-weight: 600;
        }
        
        .tab:hover {
            color: #667eea;
        }
        
        .tab-content {
            display: none;
        }
        
        .tab-content.active {
            display: block;
            animation: fadeIn 0.3s;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .module {
            background: #f8f9fa;
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 20px;
        }
        
        .module h3 {
            color: #333;
            margin-bottom: 20px;
            font-size: 1.4em;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .module-icon {
            font-size: 1.5em;
        }
        
        .input-group {
            margin-bottom: 20px;
        }
        
        label {
            display: block;
            margin-bottom: 8px;
            color: #555;
            font-weight: 500;
        }
        
        input[type="range"] {
            width: 100%;
            height: 8px;
            border-radius: 5px;
            background: #e0e0e0;
            outline: none;
            -webkit-appearance: none;
        }
        
        input[type="range"]::-webkit-slider-thumb {
            -webkit-appearance: none;
            appearance: none;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background: #667eea;
            cursor: pointer;
        }
        
        input[type="range"]::-moz-range-thumb {
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background: #667eea;
            cursor: pointer;
            border: none;
        }
        
        .range-labels {
            display: flex;
            justify-content: space-between;
            margin-top: 5px;
            font-size: 0.9em;
            color: #888;
        }
        
        .value-display {
            display: inline-block;
            background: #667eea;
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-weight: 600;
            margin-left: 10px;
        }
        
        select, input[type="text"], textarea {
            width: 100%;
            padding: 12px;
            border: 2px solid #e0e0e0;
            border-radius: 8px;
            font-size: 1em;
            transition: border-color 0.3s;
        }
        
        select:focus, input[type="text"]:focus, textarea:focus {
            outline: none;
            border-color: #667eea;
        }
        
        textarea {
            resize: vertical;
            min-height: 80px;
        }
        
        .checkbox-group {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        
        .checkbox-item {
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        input[type="checkbox"] {
            width: 20px;
            height: 20px;
            cursor: pointer;
        }
        
        .btn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            padding: 15px 40px;
            font-size: 1.1em;
            border-radius: 10px;
            cursor: pointer;
            font-weight: 600;
            transition: transform 0.2s, box-shadow 0.2s;
        }
        
        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(102, 126, 234, 0.3);
        }
        
        .btn:active {
            transform: translateY(0);
        }
        
        .vhs-display {
            text-align: center;
            padding: 30px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border-radius: 15px;
            margin: 20px 0;
        }
        
        .vhs-score {
            font-size: 4em;
            font-weight: bold;
            margin: 20px 0;
        }
        
        .vhs-label {
            font-size: 1.3em;
            opacity: 0.9;
        }
        
        .vhs-interpretation {
            margin-top: 20px;
            padding: 15px;
            background: rgba(255,255,255,0.2);
            border-radius: 10px;
            font-size: 1.1em;
        }
        
        .phase-card {
            background: white;
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 20px;
            border-left: 5px solid #667eea;
        }
        
        .phase-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .phase-title {
            font-size: 1.4em;
            color: #667eea;
            font-weight: 600;
        }
        
        .phase-status {
            padding: 8px 20px;
            background: #e8f0fe;
            color: #667eea;
            border-radius: 20px;
            font-weight: 600;
        }
        
        .phase-status.completed {
            background: #d4edda;
            color: #155724;
        }
        
        .phase-status.locked {
            background: #f8d7da;
            color: #721c24;
        }
        
        .progress-bar {
            width: 100%;
            height: 20px;
            background: #e0e0e0;
            border-radius: 10px;
            overflow: hidden;
            margin: 15px 0;
        }
        
        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, #667eea 0%, #764ba2 100%);
            transition: width 0.5s;
            display: flex;
            align-items: center;
            justify-content: flex-end;
            padding-right: 10px;
            color: white;
            font-weight: 600;
            font-size: 0.9em;
        }
        
        .milestone-list {
            list-style: none;
            margin-top: 15px;
        }
        
        .milestone-item {
            padding: 10px;
            margin: 8px 0;
            background: #f8f9fa;
            border-radius: 8px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .milestone-item.completed {
            background: #d4edda;
        }
        
        .milestone-icon {
            font-size: 1.2em;
        }
        
        .achievement-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .achievement-card {
            background: white;
            border-radius: 15px;
            padding: 20px;
            text-align: center;
            border: 3px solid #e0e0e0;
            transition: all 0.3s;
        }
        
        .achievement-card.unlocked {
            border-color: #667eea;
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.2);
        }
        
        .achievement-card.locked {
            opacity: 0.5;
        }
        
        .achievement-icon {
            font-size: 3em;
            margin-bottom: 10px;
        }
        
        .achievement-title {
            font-weight: 600;
            color: #333;
            margin-bottom: 8px;
        }
        
        .achievement-desc {
            font-size: 0.9em;
            color: #666;
        }
        
        .recommendation-box {
            background: #fff3cd;
            border-left: 5px solid #ffc107;
            padding: 20px;
            border-radius: 10px;
            margin: 15px 0;
        }
        
        .recommendation-box h4 {
            color: #856404;
            margin-bottom: 10px;
        }
        
        .recommendation-box p {
            color: #856404;
            line-height: 1.6;
        }
        
        .chart-container {
            background: white;
            padding: 20px;
            border-radius: 15px;
            margin: 20px 0;
        }
        
        .stat-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .stat-card {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 25px;
            border-radius: 15px;
            text-align: center;
        }
        
        .stat-value {
            font-size: 3em;
            font-weight: bold;
            margin: 10px 0;
        }
        
        .stat-label {
            font-size: 1.1em;
            opacity: 0.9;
        }
        
        .entry-list {
            margin-top: 20px;
        }
        
        .entry-item {
            background: white;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 15px;
            border-left: 4px solid #667eea;
        }
        
        .entry-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
            font-weight: 600;
            color: #333;
        }
        
        .entry-details {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 10px;
            margin-top: 10px;
        }
        
        .entry-detail {
            font-size: 0.9em;
            color: #666;
        }
        
        .alert {
            padding: 15px 20px;
            border-radius: 10px;
            margin: 15px 0;
        }
        
        .alert-success {
            background: #d4edda;
            border-left: 4px solid #28a745;
            color: #155724;
        }
        
        .alert-info {
            background: #d1ecf1;
            border-left: 4px solid #17a2b8;
            color: #0c5460;
        }
        
        .alert-warning {
            background: #fff3cd;
            border-left: 4px solid #ffc107;
            color: #856404;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🎯 V-HS Progress Tracker</h1>
        <p class="subtitle">Visceral Hypersensitivity Management & Nervous System Retraining</p>
        
        <div class="tabs">
            <button class="tab active" onclick="switchTab('daily-input')">Daily Input</button>
            <button class="tab" onclick="switchTab('dashboard')">Dashboard</button>
            <button class="tab" onclick="switchTab('progress')">Progress</button>
            <button class="tab" onclick="switchTab('achievements')">Achievements</button>
            <button class="tab" onclick="switchTab('history')">History</button>
        </div>
        
        <!-- DAILY INPUT TAB -->
        <div id="daily-input" class="tab-content active">
            <div class="module">
                <h3><span class="module-icon">💢</span>Physical Pain & Sensation</h3>
                
                <div class="input-group">
                    <label>Pain Intensity <span class="value-display" id="pain-value">5</span></label>
                    <input type="range" id="pain-intensity" min="0" max="10" value="5" oninput="updateValue('pain')">
                    <div class="range-labels">
                        <span>No Pain (0)</span>
                        <span>Worst Pain (10)</span>
                    </div>
                </div>
                
                <div class="input-group">
                    <label>Pain Location</label>
                    <select id="pain-location">
                        <option value="none">No specific pain</option>
                        <option value="upper">Upper Abdomen</option>
                        <option value="lower">Lower Abdomen</option>
                        <option value="diffuse">Diffuse</option>
                        <option value="left">Left Side</option>
                        <option value="right">Right Side</option>
                    </select>
                </div>
                
                <div class="input-group">
                    <label>Pain Character</label>
                    <div class="checkbox-group">
                        <div class="checkbox-item">
                            <input type="checkbox" id="cramping" value="cramping">
                            <label for="cramping">Cramping</label>
                        </div>
                        <div class="checkbox-item">
                            <input type="checkbox" id="burning" value="burning">
                            <label for="burning">Burning</label>
                        </div>
                        <div class="checkbox-item">
                            <input type="checkbox" id="pressure" value="pressure">
                            <label for="pressure">Pressure</label>
                        </div>
                        <div class="checkbox-item">
                            <input type="checkbox" id="sharp" value="sharp">
                            <label for="sharp">Sharp</label>
                        </div>
                        <div class="checkbox-item">
                            <input type="checkbox" id="dull" value="dull">
                            <label for="dull">Dull</label>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="module">
                <h3><span class="module-icon">😰</span>Emotional Response</h3>
                
                <div class="input-group">
                    <label>Anxiety About Symptoms <span class="value-display" id="anxiety-value">5</span></label>
                    <input type="range" id="anxiety-level" min="0" max="10" value="5" oninput="updateValue('anxiety')">
                    <div class="range-labels">
                        <span>No Anxiety (0)</span>
                        <span>Extreme Anxiety (10)</span>
                    </div>
                </div>
                
                <div class="input-group">
                    <label>Overall Distress Level <span class="value-display" id="distress-value">5</span></label>
                    <input type="range" id="distress-level" min="0" max="10" value="5" oninput="updateValue('distress')">
                    <div class="range-labels">
                        <span>No Distress (0)</span>
                        <span>Extreme Distress (10)</span>
                    </div>
                </div>
                
                <div class="input-group">
                    <label>Did you experience catastrophizing thoughts today?</label>
                    <div class="checkbox-group">
                        <div class="checkbox-item">
                            <input type="checkbox" id="catastrophizing">
                            <label for="catastrophizing">Yes, I had "what if" or worst-case scenario thoughts</label>
                        </div>
                    </div>
                </div>
                
                <div class="input-group">
                    <label>Catastrophizing Thoughts (optional notes)</label>
                    <textarea id="catastrophizing-notes" placeholder="Briefly describe any anxious thoughts..."></textarea>
                </div>
                
                <div class="input-group">
                    <label>How many times did you check/monitor symptoms today?</label>
                    <input type="number" id="checking-count" min="0" value="0" style="width: 150px;">
                </div>
            </div>
            
            <div class="module">
                <h3><span class="module-icon">✨</span>Comfort & Function</h3>
                
                <div class="input-group">
                    <label>Overall Wellbeing <span class="value-display" id="wellbeing-value">5</span></label>
                    <input type="range" id="wellbeing" min="0" max="10" value="5" oninput="updateValue('wellbeing')">
                    <div class="range-labels">
                        <span>Terrible (0)</span>
                        <span>Perfect (10)</span>
                    </div>
                </div>
                
                <div class="input-group">
                    <label>Did you have an unexpected comfort moment today?</label>
                    <div class="checkbox-group">
                        <div class="checkbox-item">
                            <input type="checkbox" id="comfort-moment">
                            <label for="comfort-moment">Yes, I felt good despite circumstances that would normally cause distress</label>
                        </div>
                    </div>
                </div>
                
                <div class="input-group">
                    <label>Comfort Moment Details (optional)</label>
                    <textarea id="comfort-notes" placeholder="What was happening? What did you notice?"></textarea>
                </div>
            </div>
            
            <div class="module">
                <h3><span class="module-icon">📋</span>Context Tracking</h3>
                
                <div class="input-group">
                    <label>Bowel Movement Today?</label>
                    <select id="bm-status">
                        <option value="no">No BM</option>
                        <option value="yes-normal">Yes - Normal</option>
                        <option value="yes-loose">Yes - Loose</option>
                        <option value="yes-hard">Yes - Hard</option>
                        <option value="multiple">Multiple BMs</option>
                    </select>
                </div>
                
                <div class="input-group">
                    <label>Stress Level <span class="value-display" id="stress-value">5</span></label>
                    <input type="range" id="stress-level" min="0" max="10" value="5" oninput="updateValue('stress')">
                    <div class="range-labels">
                        <span>No Stress (0)</span>
                        <span>Extreme Stress (10)</span>
                    </div>
                </div>
                
                <div class="input-group">
                    <label>Sleep Quality <span class="value-display" id="sleep-value">5</span></label>
                    <input type="range" id="sleep-quality" min="0" max="10" value="5" oninput="updateValue('sleep')">
                    <div class="range-labels">
                        <span>Terrible (0)</span>
                        <span>Perfect (10)</span>
                    </div>
                </div>
                
                <div class="input-group">
                    <label>Additional Notes</label>
                    <textarea id="daily-notes" placeholder="Any other observations, triggers, or patterns you noticed..."></textarea>
                </div>
            </div>
            
            <div style="text-align: center; margin-top: 30px;">
                <button class="btn" onclick="saveEntry()">💾 Save Today's Entry</button>
            </div>
            
            <div id="save-message" class="alert alert-success" style="display: none; margin-top: 20px;">
                ✅ Entry saved successfully! Check your Dashboard for analysis.
            </div>
        </div>
        
        <!-- DASHBOARD TAB -->
        <div id="dashboard" class="tab-content">
            <div class="vhs-display">
                <div class="vhs-label">Your V-HS Hypersensitivity Gap</div>
                <div class="vhs-score" id="current-vhs">--</div>
                <div class="vhs-interpretation" id="vhs-interpretation">
                    Complete today's entry to see your V-HS gap score
                </div>
            </div>
            
            <div class="stat-grid">
                <div class="stat-card">
                    <div class="stat-label">Current Phase</div>
                    <div class="stat-value" id="current-phase-num">1</div>
                    <div class="stat-label" id="current-phase-name">Recognition</div>
                </div>
                
                <div class="stat-card">
                    <div class="stat-label">Comfort Days</div>
                    <div class="stat-value" id="comfort-days-count">0</div>
                    <div class="stat-label">This Month</div>
                </div>
                
                <div class="stat-card">
                    <div class="stat-label">Tracking Streak</div>
                    <div class="stat-value" id="tracking-streak">0</div>
                    <div class="stat-label">Days</div>
                </div>
            </div>
            
            <div id="recommendations-container">
                <!-- Recommendations will be generated here -->
            </div>
            
            <div class="chart-container">
                <h3>7-Day Trend</h3>
                anvas id="trendChart" width="800" height="300"></canvas>
            </div>
        </div>
        
        <!-- PROGRESS TAB -->
        <div id="progress" class="tab-content">
            <h2 style="margin-bottom: 20px;">Phase Progression</h2>
            
            <div id="phases-container">
                <!-- Phases will be dynamically generated -->
            </div>
        </div>
        
        <!-- ACHIEVEMENTS TAB -->
        <div id="achievements" class="tab-content">
            <h2 style="margin-bottom: 20px;">Your Achievements</h2>
            
            <div class="achievement-grid" id="achievements-grid">
                <!-- Achievements will be dynamically generated -->
            </div>
        </div>
        
        <!-- HISTORY TAB -->
        <div id="history" class="tab-content">
            <h2 style="margin-bottom: 20px;">Entry History</h2>
            
            <div class="entry-list" id="entry-list">
                <!-- Entry history will be displayed here -->
            </div>
        </div>
    </div>
    
    <script>
        // Data storage
        let appData = {
            entries: [],
            currentPhase: 1,
            achievements: [],
            startDate: new Date().toISOString()
        };
        
        // Load data from localStorage
        function loadData() {
            const saved = localStorage.getItem('vhsTrackerData');
            if (saved) {
                appData = JSON.parse(saved);
            }
            initializeAchievements();
        }
        
        // Save data to localStorage
        function saveData() {
            localStorage.setItem('vhsTrackerData', JSON.stringify(appData));
        }
        
        // Initialize achievements
        function initializeAchievements() {
            const achievementsList = [
                { id: 'first-entry', name: 'First Step', desc: 'Complete your first entry', icon: '🎯', unlocked: false },
                { id: 'week-streak', name: 'Consistent Tracker', desc: '7 days of tracking', icon: '📅', unlocked: false },
                { id: 'first-comfort', name: 'First Comfort Day', desc: 'Experience your first unexpected comfort day', icon: '✨', unlocked: false },
                { id: 'vhs-improvement', name: 'Gap Narrowing', desc: 'V-HS gap reduced by 25%', icon: '📉', unlocked: false },
                { id: 'no-catastrophize', name: 'Clear Mind', desc: '7 days without catastrophizing', icon: '🧘', unlocked: false },
                { id: 'phase-2', name: 'Breaking the Loop', desc: 'Advanced to Phase 2', icon: '🚀', unlocked: false },
                { id: 'low-anxiety', name: 'Calm Response', desc: 'Pain high but anxiety low', icon: '😌', unlocked: false },
                { id: 'month-complete', name: 'Monthly Milestone', desc: '30 days of tracking', icon: '🏆', unlocked: false }
            ];
            
            if (appData.achievements.length === 0) {
                appData.achievements = achievementsList;
            }
        }
        
        // Switch between tabs
        function switchTab(tabName) {
            // Hide all tabs
            document.querySelectorAll('.tab-content').forEach(tab => {
                tab.classList.remove('active');
            });
            document.querySelectorAll('.tab').forEach(tab => {
                tab.classList.remove('active');
            });
            
            // Show selected tab
            document.getElementById(tabName).classList.add('active');
            event.target.classList.add('active');
            
            // Update content based on tab
            if (tabName === 'dashboard') {
                updateDashboard();
            } else if (tabName === 'progress') {
                updateProgressTab();
            } else if (tabName === 'achievements') {
                updateAchievementsTab();
            } else if (tabName === 'history') {
                updateHistoryTab();
            }
        }
        
        // Update slider value displays
        function updateValue(type) {
            const slider = document.getElementById(`${type}-${type === 'pain' ? 'intensity' : type === 'anxiety' || type === 'distress' || type === 'stress' || type === 'wellbeing' || type === 'sleep' ? 'level' : 'quality'}`);
            const display = document.getElementById(`${type}-value`);
            
            if (type === 'pain') {
                display.textContent = document.getElementById('pain-intensity').value;
            } else if (type === 'anxiety') {
                display.textContent = document.getElementById('anxiety-level').value;
            } else if (type === 'distress') {
                display.textContent = document.getElementById('distress-level').value;
            } else if (type === 'stress') {
                display.textContent = document.getElementById('stress-level').value;
            } else if (type === 'wellbeing') {
                display.textContent = document.getElementById('wellbeing').value;
            } else if (type === 'sleep') {
                display.textContent = document.getElementById('sleep-quality').value;
            }
        }
        
        // Calculate V-HS gap
        function calculateVHSGap(painIntensity, distressLevel) {
            return Math.abs(distressLevel - painIntensity);
        }
        
        // Get pain character selections
        function getPainCharacters() {
            const characters = [];
            ['cramping', 'burning', 'pressure', 'sharp', 'dull'].forEach(char => {
                if (document.getElementById(char).checked) {
                    characters.push(char);
                }
            });
            return characters;
        }
        
        // Save daily entry
        function saveEntry() {
            const entry = {
                date: new Date().toISOString(),
                painIntensity: parseInt(document.getElementById('pain-intensity').value),
                painLocation: document.getElementById('pain-location').value,
                painCharacters: getPainCharacters(),
                anxietyLevel: parseInt(document.getElementById('anxiety-level').value),
                distressLevel: parseInt(document.getElementById('distress-level').value),
                catastrophizing: document.getElementById('catastrophizing').checked,
                catastrophizingNotes: document.getElementById('catastrophizing-notes').value,
                checkingCount: parseInt(document.getElementById('checking-count').value),
                wellbeing: parseInt(document.getElementById('wellbeing').value),
                comfortMoment: document.getElementById('comfort-moment').checked,
                comfortNotes: document.getElementById('comfort-notes').value,
                bmStatus: document.getElementById('bm-status').value,
                stressLevel: parseInt(document.getElementById('stress-level').value),
                sleepQuality: parseInt(document.getElementById('sleep-quality').value),
                notes: document.getElementById('daily-notes').value
            };
            
            // Calculate V-HS gap
            entry.vhsGap = calculateVHSGap(entry.painIntensity, entry.distressLevel);
            
            // Add to entries
            appData.entries.push(entry);
            
            // Check for achievements
            checkAchievements(entry);
            
            // Save data
            saveData();
            
            // Show success message
            const message = document.getElementById('save-message');
            message.style.display = 'block';
            setTimeout(() => {
                message.style.display = 'none';
            }, 3000);
            
            // Switch to dashboard
            setTimeout(() => {
                switchTab('dashboard');
                document.querySelector('.tab:nth-child(2)').classList.add('active');
            }, 1500);
        }
        
        // Check and unlock achievements
        function checkAchievements(latestEntry) {
            // First entry
            if (appData.entries.length === 1) {
                unlockAchievement('first-entry');
            }
            
            // First comfort day
            if (latestEntry.comfortMoment && !appData.achievements.find(a => a.id === 'first-comfort').unlocked) {
                unlockAchievement('first-comfort');
            }
            
            // 7-day streak
            if (appData.entries.length >= 7) {
                unlockAchievement('week-streak');
            }
            
            // 30-day streak
            if (appData.entries.length >= 30) {
                unlockAchievement('month-complete');
            }
            
            // Low anxiety despite pain
            if (latestEntry.painIntensity >= 6 && latestEntry.anxietyLevel <= 3) {
                unlockAchievement('low-anxiety');
            }
            
            // Check for no catastrophizing streak
            const last7 = appData.entries.slice(-7);
            if (last7.length === 7 && last7.every(e => !e.catastrophizing)) {
                unlockAchievement('no-catastrophize');
            }
            
            // V-HS improvement
            if (appData.entries.length >= 7) {
                const baseline = appData.entries.slice(0, 7).reduce((sum, e) => sum + e.vhsGap, 0) / 7;
                const recent = appData.entries.slice(-7).reduce((sum, e) => sum + e.vhsGap, 0) / 7;
                if (recent <= baseline * 0.75) {
                    unlockAchievement('vhs-improvement');
                }
            }
        }
        
        function unlockAchievement(achievementId) {
            const achievement = appData.achievements.find(a => a.id === achievementId);
            if (achievement && !achievement.unlocked) {
                achievement.unlocked = true;
                achievement.unlockedDate = new Date().toISOString();
                saveData();
            }
        }
        
        // Update dashboard
        function updateDashboard() {
            if (appData.entries.length === 0) {
                return;
            }
            
            const latest = appData.entries[appData.entries.length - 1];
            
            // Update V-HS display
            document.getElementById('current-vhs').textContent = latest.vhsGap.toFixed(1);
            
            // Interpretation
            let interpretation = '';
            if (latest.vhsGap < 2) {
                interpretation = '🎉 Excellent regulation! Your nervous system is responding well to sensations without overreacting.';
            } else if (latest.vhsGap < 4) {
                interpretation = '👍 Good progress. Your emotional response is becoming more balanced relative to physical sensations.';
            } else if (latest.vhsGap < 6) {
                interpretation = '📊 Moderate hypersensitivity. Your nervous system is still amplifying sensations, but you\'re on the right track.';
            } else {
                interpretation = '⚠️ High hypersensitivity detected. Your nervous system is strongly amplifying gut sensations. Focus on retraining techniques.';
            }
            document.getElementById('vhs-interpretation').textContent = interpretation;
            
            // Update stats
            document.getElementById('current-phase-num').textContent = appData.currentPhase;
            const phaseNames = ['', 'Recognition', 'Breaking Loop', 'Retraining', 'Maintenance'];
            document.getElementById('current-phase-name').textContent = phaseNames[appData.currentPhase];
            
            // Comfort days this month
            const thisMonth = appData.entries.filter(e => {
                const entryDate = new Date(e.date);
                const now = new Date();
                return entryDate.getMonth() === now.getMonth() && e.comfortMoment;
            });
            document.getElementById('comfort-days-count').textContent = thisMonth.length;
            
            // Tracking streak
            document.getElementById('tracking-streak').textContent = appData.entries.length;
            
            // Generate recommendations
            generateRecommendations(latest);
        }
        
        // Generate personalized recommendations
        function generateRecommendations(entry) {
            const container = document.getElementById('recommendations-container');
            container.innerHTML = '';
            
            // High pain + high anxiety
            if (entry.painIntensity >= 7 && entry.anxietyLevel >= 7) {
                container.innerHTML += `
                    <div class="recommendation-box">
                        <h4>🎯 Today's Focus: Nervous System Calming</h4>
                        <p>Your nervous system is amplifying pain signals. Try a 10-minute guided body scan meditation to reduce the pain-anxiety coupling. Remember: high pain doesn't always mean danger, especially with V-HS.</p>
                    </div>
                `;
            }
            
            // High pain + low anxiety (good!)
            if (entry.painIntensity >= 6 && entry.anxietyLevel <= 3) {
                container.innerHTML += `
                    <div class="recommendation-box" style="background: #d4edda; border-left-color: #28a745;">
                        <h4 style="color: #155724;">🎉 Excellent Regulation!</h4>
                        <p style="color: #155724;">Your brain is learning that pain doesn't equal danger. This decoupling is exactly what V-HS retraining looks like. Continue your current approach—it's working!</p>
                    </div>
                `;
            }
            
            // Low pain + high anxiety (pure V-HS)
            if (entry.painIntensity <= 3 && entry.anxietyLevel >= 6) {
                container.innerHTML += `
                    <div class="recommendation-box">
                        <h4>🧠 Pure Hypersensitivity Pattern</h4>
                        <p>Your anxiety is high despite low physical symptoms. This indicates your nervous system is in hypervigilance mode rather than responding to actual problems. Practice cognitive reframing: "My gut feels fine. This is just my nervous system being cautious."</p>
                    </div>
                `;
            }
            
            // Comfort moment
            if (entry.comfortMoment) {
                container.innerHTML += `
                    <div class="recommendation-box" style="background: #d1ecf1; border-left-color: #17a2b8;">
                        <h4 style="color: #0c5460;">✨ Comfort Day Noted!</h4>
                        <p style="color: #0c5460;">Document what factors were present today. Your nervous system is successfully recalibrating. These comfort days are evidence of genuine neurological healing.</p>
                    </div>
                `;
            }
            
            // Catastrophizing
            if (entry.catastrophizing) {
                container.innerHTML += `
                    <div class="recommendation-box">
                        <h4>💭 Catastrophizing Detected</h4>
                        <p>When "what if" thoughts arise, try the 5-4-3-2-1 grounding technique: Name 5 things you see, 4 you can touch, 3 you hear, 2 you smell, 1 you taste. This interrupts the catastrophizing loop.</p>
                    </div>
                `;
            }
        }
        
        // Update progress tab
        function updateProgressTab() {
            const container = document.getElementById('phases-container');
            
            const phases = [
                {
                    number: 1,
                    name: 'Recognition',
                    duration: 'Weeks 1-4',
                    goals: [
                        'Establish baseline patterns',
                        'Identify catastrophizing triggers',
                        'Distinguish physical sensation from fear'
                    ],
                    milestones: [
                        { text: '14 days of tracking', completed: appData.entries.length >= 14 },
                        { text: 'First comfort moment', completed: appData.entries.some(e => e.comfortMoment) },
                        { text: 'Identified pain-anxiety patterns', completed: appData.entries.length >= 7 }
                    ]
                },
                {
                    number: 2,
                    name: 'Breaking the Loop',
                    duration: 'Weeks 5-12',
                    goals: [
                        'Reduce catastrophizing by 30%',
                        'Experience first comfort days',
                        'Lower anxiety despite pain'
                    ],
                    milestones: [
                        { text: '3 comfort days recorded', completed: appData.entries.filter(e => e.comfortMoment).length >= 3 },
                        { text: 'V-HS gap narrowed 25%', completed: false },
                        { text: '7 days no catastrophizing', completed: false }
                    ]
                },
                {
                    number: 3,
                    name: 'Active Retraining',
                    duration: 'Weeks 13-24',
                    goals: [
                        'Sustained pain-anxiety decoupling',
                        'Consistent comfort with variations',
                        'No catastrophizing spirals'
                    ],
                    milestones: [
                        { text: 'V-HS gap under 2', completed: false },
                        { text: '50% comfort days per month', completed: false },
                        { text: 'Zero anxiety spikes', completed: false }
                    ]
                },
                {
                    number: 4,
                    name: 'Consolidation',
                    duration: '6+ months',
                    goals: [
                        'Sustained nervous system regulation',
                        'Comfort becomes baseline',
                        'Handle flares without backsliding'
                    ],
                    milestones: [
                        { text: '80% comfort days', completed: false },
                        { text: 'Pain without anxiety', completed: false },
                        { text: 'Sustained for 3 months', completed: false }
                    ]
                }
            ];
            
            container.innerHTML = '';
            
            phases.forEach(phase => {
                const isCurrentPhase = phase.number === appData.currentPhase;
                const isPastPhase = phase.number < appData.currentPhase;
                const completedMilestones = phase.milestones.filter(m => m.completed).length;
                const totalMilestones = phase.milestones.length;
                const progress = (completedMilestones / totalMilestones) * 100;
                
                let status = 'locked';
                if (isPastPhase) status = 'completed';
                if (isCurrentPhase) status = 'current';
                
                const html = `
                    <div class="phase-card">
                        <div class="phase-header">
                            <div class="phase-title">Phase ${phase.number}: ${phase.name}</div>
                            <div class="phase-status ${status}">
                                ${status === 'completed' ? '✅ Completed' : status === 'current' ? '🔄 In Progress' : '🔒 Locked'}
                            </div>
                        </div>
                        <p style="color: #666; margin-bottom: 15px;">${phase.duration}</p>
                        
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: ${progress}%">
                                ${progress > 15 ? Math.round(progress) + '%' : ''}
                            </div>
                        </div>
                        
                        <h4 style="margin: 20px 0 10px 0;">Goals:</h4>
                        <ul style="padding-left: 20px; color: #666;">
                            ${phase.goals.map(goal => `<li style="margin: 5px 0;">${goal}</li>`).join('')}
                        </ul>
                        
                        <h4 style="margin: 20px 0 10px 0;">Milestones:</h4>
                        <ul class="milestone-list">
                            ${phase.milestones.map(milestone => `
                                <li class="milestone-item ${milestone.completed ? 'completed' : ''}">
                                    <span class="milestone-icon">${milestone.completed ? '✅' : '⬜'}</span>
                                    ${milestone.text}
                                </li>
                            `).join('')}
                        </ul>
                    </div>
                `;
                
                container.innerHTML += html;
            });
        }
        
        // Update achievements tab
        function updateAchievementsTab() {
            const container = document.getElementById('achievements-grid');
            container.innerHTML = '';
            
            appData.achievements.forEach(achievement => {
                const html = `
                    <div class="achievement-card ${achievement.unlocked ? 'unlocked' : 'locked'}">
                        <div class="achievement-icon">${achievement.icon}</div>
                        <div class="achievement-title">${achievement.name}</div>
                        <div class="achievement-desc">${achievement.desc}</div>
                        ${achievement.unlocked ? `<div style="margin-top: 10px; color: #28a745; font-weight: 600;">Unlocked!</div>` : ''}
                    </div>
                `;
                container.innerHTML += html;
            });
        }
        
        // Update history tab
        function updateHistoryTab() {
            const container = document.getElementById('entry-list');
            
            if (appData.entries.length === 0) {
                container.innerHTML = '<p style="text-align: center; color: #666; padding: 40px;">No entries yet. Start tracking on the Daily Input tab!</p>';
                return;
            }
            
            container.innerHTML = '';
            
            // Show most recent entries first
            const recentEntries = [...appData.entries].reverse().slice(0, 30);
            
            recentEntries.forEach(entry => {
                const date = new Date(entry.date);
                const dateStr = date.toLocaleDateString('en-US', { weekday: 'short', month: 'short', day: 'numeric', year: 'numeric' });
                
                const html = `
                    <div class="entry-item">
                        <div class="entry-header">
                            <span>${dateStr}</span>
                            <span>V-HS Gap: ${entry.vhsGap.toFixed(1)}</span>
                        </div>
                        <div class="entry-details">
                            <div class="entry-detail">Pain: ${entry.painIntensity}/10</div>
                            <div class="entry-detail">Anxiety: ${entry.anxietyLevel}/10</div>
                            <div class="entry-detail">Distress: ${entry.distressLevel}/10</div>
                            <div class="entry-detail">Wellbeing: ${entry.wellbeing}/10</div>
                            <div class="entry-detail">BM: ${entry.bmStatus}</div>
                            <div class="entry-detail">Sleep: ${entry.sleepQuality}/10</div>
                        </div>
                        ${entry.comfortMoment ? '<div style="margin-top: 10px; color: #28a745;">✨ Comfort day!</div>' : ''}
                        ${entry.catastrophizing ? '<div style="margin-top: 10px; color: #ffc107;">💭 Catastrophizing noted</div>' : ''}
                    </div>
                `;
                container.innerHTML += html;
            });
        }
        
        // Initialize app
        window.onload = function() {
            loadData();
            updateDashboard();
        };
    </script>
</body>
</html>
