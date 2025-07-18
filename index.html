<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>URL Shortener</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 20px;
            margin-bottom: 30px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
        }

        .header h1 {
            color: #333;
            font-size: 2.5em;
            margin-bottom: 10px;
            text-align: center;
        }

        .header p {
            color: #666;
            text-align: center;
            font-size: 1.1em;
        }

        .stats-badge {
            position: absolute;
            top: 20px;
            right: 20px;
            background: rgba(103, 126, 234, 0.9);
            color: white;
            padding: 10px 15px;
            border-radius: 25px;
            font-weight: bold;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        .tabs {
            display: flex;
            justify-content: center;
            margin-bottom: 30px;
        }

        .tab {
            background: rgba(255, 255, 255, 0.2);
            border: none;
            padding: 15px 30px;
            margin: 0 10px;
            border-radius: 10px;
            color: white;
            font-size: 1.1em;
            cursor: pointer;
            transition: all 0.3s ease;
            backdrop-filter: blur(10px);
        }

        .tab:hover {
            background: rgba(255, 255, 255, 0.3);
            transform: translateY(-2px);
        }

        .tab.active {
            background: rgba(255, 255, 255, 0.9);
            color: #333;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        .content {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
        }

        .url-form {
            border: 2px solid #e1e5e9;
            border-radius: 12px;
            padding: 20px;
            margin-bottom: 20px;
            background: #f8f9fa;
            transition: all 0.3s ease;
        }

        .url-form:hover {
            border-color: #667eea;
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.1);
        }

        .url-form.has-result {
            border-color: #28a745;
            background: #f8fff8;
        }

        .form-title {
            font-size: 1.2em;
            font-weight: bold;
            color: #333;
            margin-bottom: 15px;
        }

        .form-row {
            display: grid;
            grid-template-columns: 2fr 1fr 1fr;
            gap: 15px;
            margin-bottom: 15px;
        }

        @media (max-width: 768px) {
            .form-row {
                grid-template-columns: 1fr;
            }
        }

        .form-group {
            display: flex;
            flex-direction: column;
        }

        .form-group label {
            margin-bottom: 5px;
            font-weight: 500;
            color: #555;
        }

        .form-group input {
            padding: 12px;
            border: 2px solid #e1e5e9;
            border-radius: 8px;
            font-size: 1em;
            transition: all 0.3s ease;
        }

        .form-group input:focus {
            outline: none;
            border-color: #667eea;
            box-shadow: 0 0 0 3px rgba(102, 126, 234, 0.1);
        }

        .error {
            color: #dc3545;
            font-size: 0.9em;
            margin-top: 5px;
        }

        .result {
            background: #e8f5e8;
            border: 1px solid #28a745;
            border-radius: 8px;
            padding: 15px;
            margin-top: 15px;
        }

        .result-title {
            color: #28a745;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .short-url-container {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 10px;
        }

        .short-url-input {
            flex: 1;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 6px;
            background: white;
            font-family: monospace;
        }

        .copy-btn, .open-btn {
            padding: 8px 12px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 0.9em;
            transition: all 0.3s ease;
        }

        .copy-btn {
            background: #6c757d;
            color: white;
        }

        .copy-btn:hover {
            background: #5a6268;
        }

        .open-btn {
            background: #007bff;
            color: white;
        }

        .open-btn:hover {
            background: #0056b3;
        }

        .expiry-info {
            font-size: 0.9em;
            color: #666;
        }

        .action-buttons {
            display: flex;
            gap: 15px;
            margin-top: 30px;
        }

        .btn {
            padding: 15px 30px;
            border: none;
            border-radius: 10px;
            font-size: 1.1em;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: bold;
        }

        .btn-primary {
            background: linear-gradient(45deg, #667eea, #764ba2);
            color: white;
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.3);
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(102, 126, 234, 0.4);
        }

        .btn-secondary {
            background: #6c757d;
            color: white;
        }

        .btn-secondary:hover {
            background: #5a6268;
        }

        .btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none;
        }

        .loading {
            display: inline-block;
            width: 20px;
            height: 20px;
            border: 2px solid #ffffff;
            border-radius: 50%;
            border-top-color: transparent;
            animation: spin 1s ease-in-out infinite;
            margin-right: 10px;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }

        .stats-grid {
            display: grid;
            gap: 20px;
        }

        .stat-card {
            background: #f8f9fa;
            border: 2px solid #e1e5e9;
            border-radius: 12px;
            padding: 20px;
            transition: all 0.3s ease;
        }

        .stat-card:hover {
            border-color: #667eea;
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.1);
        }

        .stat-card.expired {
            border-color: #dc3545;
            background: #fff5f5;
        }

        .stat-header {
            display: flex;
            justify-content: between;
            align-items: flex-start;
            margin-bottom: 15px;
        }

        .stat-info {
            flex: 1;
        }

        .stat-actions {
            display: flex;
            gap: 10px;
        }

        .stat-url {
            font-size: 1.2em;
            font-weight: bold;
            color: #333;
            margin-bottom: 5px;
            font-family: monospace;
        }

        .stat-original {
            color: #666;
            margin-bottom: 10px;
            word-break: break-all;
        }

        .stat-meta {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-bottom: 15px;
        }

        .stat-chip {
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 0.9em;
            font-weight: 500;
        }

        .stat-chip.created {
            background: #e3f2fd;
            color: #1976d2;
        }

        .stat-chip.expires {
            background: #fff3e0;
            color: #f57c00;
        }

        .stat-chip.expired {
            background: #ffebee;
            color: #d32f2f;
        }

        .stat-chip.clicks {
            background: #e8f5e9;
            color: #388e3c;
        }

        .click-details {
            margin-top: 15px;
            padding-top: 15px;
            border-top: 1px solid #e1e5e9;
        }

        .click-details h4 {
            margin-bottom: 10px;
            color: #333;
        }

        .click-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }

        .click-table th,
        .click-table td {
            padding: 10px;
            text-align: left;
            border-bottom: 1px solid #e1e5e9;
        }

        .click-table th {
            background: #f8f9fa;
            font-weight: 600;
            color: #333;
        }

        .click-table tr:hover {
            background: #f8f9fa;
        }

        .toggle-btn {
            background: none;
            border: 1px solid #667eea;
            color: #667eea;
            padding: 8px 16px;
            border-radius: 6px;
            cursor: pointer;
            font-size: 0.9em;
            transition: all 0.3s ease;
        }

        .toggle-btn:hover {
            background: #667eea;
            color: white;
        }

        .no-data {
            text-align: center;
            padding: 40px;
            color: #666;
        }

        .no-data h3 {
            margin-bottom: 10px;
            color: #333;
        }

        .alert {
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        .alert-info {
            background: #d1ecf1;
            border: 1px solid #b8daff;
            color: #0c5460;
        }

        .hidden {
            display: none;
        }

        .click-source {
            background: #667eea;
            color: white;
            padding: 4px 8px;
            border-radius: 12px;
            font-size: 0.8em;
        }

        .click-location {
            display: flex;
            align-items: center;
            gap: 5px;
        }

        .location-icon {
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="stats-badge" id="statsBadge">0 URLs Created</div>
        
        <div class="header">
            <h1>🔗 URL Shortener</h1>
            <p>Create shortened URLs with analytics and custom expiry times</p>
        </div>

        <div class="tabs">
            <button class="tab active" onclick="switchTab(0)">🔗 URL Shortener</button>
            <button class="tab" onclick="switchTab(1)">📊 Statistics</button>
        </div>

        <div class="content" id="shortenerContent">
            <h2>Create Short URLs</h2>
            <p style="color: #666; margin-bottom: 30px;">Create up to 5 shortened URLs at once. Default validity is 30 minutes.</p>
            
            <div id="urlForms">
                <!-- URL forms will be generated here -->
            </div>

            <div class="action-buttons">
                <button class="btn btn-primary" id="createBtn" onclick="createShortLinks()">
                    🔗 Create Short URLs
                </button>
                <button class="btn btn-secondary" onclick="clearForms()">
                    🗑️ Clear All
                </button>
            </div>
        </div>

        <div class="content hidden" id="statsContent">
            <h2>📊 URL Statistics</h2>
            <p style="color: #666; margin-bottom: 30px;">View analytics and performance data for all your shortened URLs.</p>
            
            <div id="statsGrid">
                <!-- Stats will be populated here -->
            </div>
        </div>
    </div>

    <script>
        // Logging Middleware Implementation
        class Logger {
            static info(message, data = {}) {
                console.log(`[INFO] ${new Date().toISOString()} - ${message}`, data);
            }
            
            static error(message, data = {}) {
                console.error(`[ERROR] ${new Date().toISOString()} - ${message}`, data);
            }
            
            static warn(message, data = {}) {
                console.warn(`[WARN] ${new Date().toISOString()} - ${message}`, data);
            }
        }

        // Application State
        let shortLinks = [];
        let activeTab = 0;
        let expandedStats = {};
        let loading = false;

        // Utility Functions
        function generateShortCode() {
            return Math.random().toString(36).substring(2, 8);
        }

        function validateURL(url) {
            try {
                new URL(url);
                return true;
            } catch {
                return false;
            }
        }

        function validateShortCode(code) {
            return /^[a-zA-Z0-9]{3,10}$/.test(code);
        }

        function getRandomLocation() {
            const locations = [
                'New York, US', 'London, UK', 'Tokyo, Japan', 'Sydney, Australia',
                'Mumbai, India', 'Berlin, Germany', 'Toronto, Canada', 'Singapore, SG'
            ];
            return locations[Math.floor(Math.random() * locations.length)];
        }

        function getRandomSource() {
            const sources = ['Direct', 'Social Media', 'Email', 'Search Engine', 'Referral'];
            return sources[Math.floor(Math.random() * sources.length)];
        }

        // Initialize Application
        function init() {
            Logger.info('URL Shortener App initialized');
            loadShortLinks();
            generateUrlForms();
            updateStatsDisplay();
        }

        // Load existing short links
        function loadShortLinks() {
            const saved = localStorage.getItem('shortLinks');
            if (saved) {
                shortLinks = JSON.parse(saved);
                Logger.info(`Loaded ${shortLinks.length} existing short links`);
            }
        }

        // Save short links
        function saveShortLinks() {
            localStorage.setItem('shortLinks', JSON.stringify(shortLinks));
            Logger.info(`Saved ${shortLinks.length} short links to storage`);
        }

        // Generate URL forms
        function generateUrlForms() {
            const container = document.getElementById('urlForms');
            container.innerHTML = '';
            
            for (let i = 0; i < 5; i++) {
                const form = document.createElement('div');
                form.className = 'url-form';
                form.innerHTML = `
                    <div class="form-title">URL #${i + 1}</div>
                    <div class="form-row">
                        <div class="form-group">
                            <label for="url_${i}">Original URL *</label>
                            <input type="url" id="url_${i}" placeholder="https://example.com/very-long-url" 
                                   oninput="validateForm(${i})">
                            <div class="error" id="error_${i}"></div>
                        </div>
                        <div class="form-group">
                            <label for="validity_${i}">Validity (minutes)</label>
                            <input type="number" id="validity_${i}" placeholder="30" min="1" 
                                   oninput="validateForm(${i})">
                        </div>
                        <div class="form-group">
                            <label for="shortcode_${i}">Custom Short Code</label>
                            <input type="text" id="shortcode_${i}" placeholder="mycode123" 
                                   oninput="validateForm(${i})">
                        </div>
                    </div>
                    <div class="result hidden" id="result_${i}">
                        <div class="result-title">✅ Short URL Created Successfully</div>
                        <div class="short-url-container">
                            <input type="text" class="short-url-input" readonly id="shorturl_${i}">
                            <button class="copy-btn" onclick="copyToClipboard('shorturl_${i}')">📋 Copy</button>
                            <button class="open-btn" onclick="openShortLink(${i})">🚀 Open</button>
                        </div>
                        <div class="expiry-info" id="expiry_${i}"></div>
                    </div>
                `;
                container.appendChild(form);
            }
        }

        // Validate individual form
        function validateForm(index) {
            const url = document.getElementById(`url_${index}`).value;
            const validity = document.getElementById(`validity_${index}`).value;
            const shortcode = document.getElementById(`shortcode_${index}`).value;
            const errorDiv = document.getElementById(`error_${index}`);
            
            errorDiv.textContent = '';
            
            if (!url) return true;
            
            if (!validateURL(url)) {
                errorDiv.textContent = 'Invalid URL format';
                return false;
            }
            
            if (validity && (isNaN(validity) || validity < 1)) {
                errorDiv.textContent = 'Validity must be a positive number';
                return false;
            }
            
            if (shortcode && !validateShortCode(shortcode)) {
                errorDiv.textContent = 'Short code must be 3-10 alphanumeric characters';
                return false;
            }
            
            if (shortcode && shortLinks.some(link => link.shortCode === shortcode)) {
                errorDiv.textContent = 'Short code already exists';
                return false;
            }
            
            return true;
        }

        // Create short links
        function createShortLinks() {
            if (loading) return;
            
            loading = true;
            const createBtn = document.getElementById('createBtn');
            createBtn.innerHTML = '<span class="loading"></span>Creating...';
            createBtn.disabled = true;
            
            Logger.info('Starting URL shortening process');
            
            let createdCount = 0;
            
            for (let i = 0; i < 5; i++) {
                const url = document.getElementById(`url_${i}`).value.trim();
                
                if (!url) continue;
                
                if (!validateForm(i)) {
                    Logger.error(`Validation failed for URL ${i + 1}`, { url });
                    continue;
                }
                
                const validity = document.getElementById(`validity_${i}`).value || 30;
                const customShortCode = document.getElementById(`shortcode_${i}`).value.trim();
                
                const shortCode = customShortCode || generateShortCode();
                const expiryDate = new Date(Date.now() + parseInt(validity) * 60 * 1000);
                
                const shortLink = {
                    id: Date.now() + i,
                    originalUrl: url,
                    shortCode,
                    shortUrl: `http://localhost:3000/${shortCode}`,
                    createdAt: new Date(),
                    expiryDate,
                    clicks: 0,
                    clickData: []
                };
                
                shortLinks.push(shortLink);
                
                // Show result
                const resultDiv = document.getElementById(`result_${i}`);
                const shortUrlInput = document.getElementById(`shorturl_${i}`);
                const expiryDiv = document.getElementById(`expiry_${i}`);
                const formDiv = resultDiv.closest('.url-form');
                
                resultDiv.classList.remove('hidden');
                formDiv.classList.add('has-result');
                shortUrlInput.value = shortLink.shortUrl;
                expiryDiv.textContent = `Expires: ${expiryDate.toLocaleString()}`;
                
                // Store reference for opening
                shortUrlInput.dataset.linkId = shortLink.id;
                
                createdCount++;
                
                Logger.info(`Short link created successfully`, {
                    shortCode,
                    originalUrl: url,
                    validity: validity + ' minutes'
                });
            }
            
            saveShortLinks();
            updateStatsDisplay();
            
            loading = false;
            createBtn.innerHTML = '🔗 Create Short URLs';
            createBtn.disabled = false;
            
            Logger.info(`URL shortening process completed. Created ${createdCount} short links`);
        }

        // Open short link
        function openShortLink(index) {
            const shortUrlInput = document.getElementById(`shorturl_${index}`);
            const linkId = parseInt(shortUrlInput.dataset.linkId);
            const shortLink = shortLinks.find(link => link.id === linkId);
            
            if (!shortLink) {
                Logger.error('Short link not found', { linkId });
                return;
            }
            
            if (new Date() > new Date(shortLink.expiryDate)) {
                Logger.warn('Attempted to access expired short link', { shortCode: shortLink.shortCode });
                alert('This short link has expired');
                return;
            }
            
            const clickData = {
                timestamp: new Date(),
                source: getRandomSource(),
                location: getRandomLocation()
            };
            
            shortLink.clicks++;
            shortLink.clickData.push(clickData);
            
            saveShortLinks();
            updateStatsDisplay();
            
            Logger.info('Short link accessed', {
                shortCode: shortLink.shortCode,
                destination: shortLink.originalUrl,
                clickData
            });
            
            window.open(shortLink.originalUrl, '_blank');
        }

        // Copy to clipboard
        function copyToClipboard(inputId) {
            const input = document.getElementById(inputId);
            input.select();
            document.execCommand('copy');
            
            Logger.info('Short URL copied to clipboard', { url: input.value });
            
            // Show feedback
            const copyBtn = input.nextElementSibling;
            const originalText = copyBtn.textContent;
            copyBtn.textContent = '✅ Copied!';
            copyBtn.style.background = '#28a745';
            
            setTimeout(() => {
                copyBtn.textContent = originalText;
                copyBtn.style.background = '#6c757d';
            }, 2000);
        }

        // Clear forms
        function clearForms() {
            for (let i = 0; i < 5; i++) {
                document.getElementById(`url_${i}`).value = '';
                document.getElementById(`validity_${i}`).value = '';
                document.getElementById(`shortcode_${i}`).value = '';
                document.getElementById(`error_${i}`).textContent = '';
                
                const resultDiv = document.getElementById(`result_${i}`);
                const formDiv = resultDiv.closest('.url-form');
                
                resultDiv.classList.add('hidden');
                formDiv.classList.remove('has-result');
            }
            
            Logger.info('URL forms cleared');
        }

        // Switch tabs
        function switchTab(tabIndex) {
            activeTab = tabIndex;
            
            // Update tab buttons
            const tabs = document.querySelectorAll('.tab');
            tabs.forEach((tab, index) => {
                tab.classList.toggle('active', index === tabIndex);
            });
            
            // Update content
            document.getElementById('shortenerContent').classList.toggle('hidden', tabIndex !== 0);
            document.getElementById('statsContent').classList.toggle('hidden', tabIndex !== 1);
            
            if (tabIndex === 1) {
                renderStatsPage();
            }
            
            Logger.info(`Switched to tab ${tabIndex}`);
        }

        // Render stats page
        function renderStatsPage() {
            const container = document.getElementById('statsGrid');
            
            if (shortLinks.length === 0) {
                container.innerHTML = `
                    <div class="alert alert-info">
                        <h3>No shortened URLs found</h3>
                        <p>Create some URLs first to see statistics.</p>
                    </div>
                `;
                return;
            }
            
            container.innerHTML = '';
            
            shortLinks.forEach(link => {
                const isExpired = new Date() > new Date(link.expiryDate);
                const card = document.createElement('div');
                card.className = `stat-card ${isExpired ? 'expired' : ''}`;
                
                card.innerHTML = `
                    <div class="stat-header">
                        <div class="stat-info">
                            <div class="stat-url">${link.shortUrl}</div>
                            <div class="stat-original">Original: ${link.originalUrl}</div>
                            <div class="stat-meta">
                                <span class="stat-chip created">📅 Created: ${new Date(link.createdAt).toLocaleString()}</span>
                                <span class="stat-chip ${isExpired ? 'expired' : 'expires'}">
                                    ⏰ ${isExpired ? 'Expired' : 'Expires'}: ${new Date(link.expiryDate).toLocaleString()}
                                </span>
                                <span class="stat-chip clicks">📊 ${link.clicks} clicks</span>
                            </div>
                        </div>
                        <div class="stat-actions">
                            <button class="copy-btn" onclick="copyStatUrl('${link.shortUrl}')">📋</button>
                            <button class="open-btn" onclick="openStatLink(${link.id})" ${isExpired ? 'disabled' : ''}>🚀</button>
                        </div>
                    </div>
                    
                    ${link.clickData.length > 0 ? `
                        <button class="toggle-btn" onclick="toggleClickDetails(${link.id})">
                            ${expandedStats[link.id] ? '▼ Hide' : '▶ Show'} Click Details
                        </button>
                        <div class="click-details ${expandedStats[link.id] ? '' : 'hidden'}" id="details_${link.id}">
                            <h4>Click Analytics</h4>
                            <table class="click-table">
                                <thead>
                                    <tr>
                                        <th>Timestamp</th>
                                        <th>Source</th>
                                        <th>Location</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    ${link.clickData.map(click => `
                                        <tr>
                                            <td>${new Date(click.timestamp).toLocaleString()}</td>
                                            <td><span class="click-source">${click.source}</span></td>
                                            <td><span class="click-location">📍 ${click.location}</span></td>
                                        </tr>
                                    `).join('')}
                                </tbody>
                            </table>
                        </div>
                    ` : ''}
                `;
                
                container.appendChild(card);
            });
        }

        // Copy stat URL
        function copyStatUrl(url) {
            navigator.clipboard.writeText(url).then(() => {
                Logger.info('Stat URL copied to clipboard', { url });
                // Could add visual feedback here
            });
        }

        // Open stat link
        function openStatLink(linkId) {
            const shortLink = shortLinks.find(link => link.id === linkId);
            if (!shortLink) return;
            
            if (new Date() > new Date(shortLink.expiryDate)) {
                alert('This short link has expired');
                return;
            }
            
            const clickData = {
                timestamp: new Date(),
                source: getRandomSource(),
                location: getRandomLocation()
            };
            
            shortLink.clicks++;
            shortLink.clickData.push(clickData);
            
            saveShortLinks();
            renderStatsPage();
            updateStatsDisplay();
            
            Logger.info('Short link accessed from stats', {
                shortCode: shortLink.shortCode,
                destination: shortLink.originalUrl,
                clickData
            });
            
            window.open(shortLink.originalUrl, '_blank');
        }

        // Toggle click details
        function toggleClickDetails(linkId) {
            expandedStats[linkId] = !expandedStats[linkId];
            renderStatsPage();
        }

        // Update stats display
        function updateStatsDisplay() {
            const badge = document.getElementById('statsBadge');
            badge.textContent = `${shortLinks.length} URLs Created`;
        }

        // Initialize app when DOM is loaded
        document.addEventListener('DOMContentLoaded', init);
    </script>
</body>
</html>