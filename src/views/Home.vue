<template>
  <div class="home">
    <header class="hero">
      <h1>OptimalPoker Pro</h1>
      <p class="subtitle">Master Preflop Strategy: From Range Construction to Advanced Analysis</p>
      <p class="description">From range construction to advanced analysis—everything at your fingertips.</p>
      
      <div class="download-section">
        <div class="free-badge">
          <span class="free-icon">🆓</span>
          <span class="free-text">100% FREE - No Hidden Costs!</span>
        </div>
        <h3>Download OptimalPoker Pro</h3>
        <div class="download-buttons">
          <button class="download-btn windows" @click="downloadWindows">
            <svg class="download-icon" viewBox="0 0 24 24" fill="currentColor">
              <path d="M3 12V6.75l6-1.32v6.48L3 12zm17-9v8.75l-10 .15V5.21L20 3zM3 13l6 .09v6.81l-6-1.15V13zm17 .25L10 13.1v6.8l10-1.75v-5.9z"/>
            </svg>
            Download for Windows
          </button>
          <button class="download-btn mac" @click="downloadMac">
            <svg class="download-icon" viewBox="0 0 24 24" fill="currentColor">
              <path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.11-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.81-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/>
            </svg>
            Download for Mac
          </button>
          <button class="download-btn linux" @click="downloadLinux">
            <svg class="download-icon" viewBox="0 0 24 24" fill="currentColor">
              <path d="M12.504 0C5.617 0 0 5.617 0 12.504S5.617 25.008 12.504 25.008 25.008 19.391 25.008 12.504 19.391 0 12.504 0zm0 23.52C6.442 23.52 1.488 18.566 1.488 12.504S6.442 1.488 12.504 1.488 23.52 6.442 23.52 12.504 18.566 23.52 12.504 23.52z"/>
              <path d="M12.504 2.976c-5.25 0-9.528 4.278-9.528 9.528s4.278 9.528 9.528 9.528 9.528-4.278 9.528-9.528-4.278-9.528-9.528-9.528zm0 18.048c-4.704 0-8.52-3.816-8.52-8.52s3.816-8.52 8.52-8.52 8.52 3.816 8.52 8.52-3.816 8.52-8.52 8.52z"/>
            </svg>
            Download for Linux
          </button>
        </div>
      </div>
    </header>

    <div class="content">
      <!-- 1. Range Construction -->
      <section class="document-section">
        <div class="section-header">
          <div class="section-number">1</div>
          <h2>Intelligent Range Construction & Analysis</h2>
        </div>
        <p class="section-intro">In OptimalPoker Pro, the OOP Range page makes it effortless to define and manage your preflop ranges. Whether you're a dedicated learner or a professional player, you can quickly build, save, and analyze ranges with precision.</p>
        
        <div class="feature-grid">
          <div class="feature-item">
            <h3>Visual Range Matrix & Analysis</h3>
            <ul>
              <li>Intuitive 13×13 hand grid for direct interaction with flexible weight adjustment</li>
              <li>Supports both manual selection and shorthand input (e.g., AKs, QQ+)</li>
              <li>Instantly generate detailed statistics: distribution of pocket pairs, suited/offsuit hands, broadway coverage, and hand strength segmentation</li>
            </ul>
          </div>
          
          <div class="feature-item">
            <h3>Advanced Extended Analysis</h3>
            <p>Gain deeper insight into postflop potential with comprehensive metrics:</p>
            <ul>
              <li>Flop hit potential (Pair+, Flush Draws, Straight Draws, Overcards)</li>
              <li>Positional strength comparison and special hand groups analysis</li>
              <li>Range polarization, playability score, and value-to-bluff ratio assessment</li>
            </ul>
          </div>
          
          <div class="feature-item">
            <h3>Efficient Range Management</h3>
            <p>Complete range management solution with advanced features:</p>
            <ul>
              <li>Save, import, and export ranges in JSON format with custom grouping</li>
              <li>One-click load for frequently used ranges—ideal for review and coaching</li>
              <li>Key card distribution (A/K/Q) and connectivity assessment tools</li>
            </ul>
          </div>
        </div>
        
        <div class="image-gallery">
          <img src="/Product_Website_Introduction/1-range/range1.png" alt="Range Matrix" />
          <img src="/Product_Website_Introduction/1-range/range2.png" alt="Range Analysis" />
        </div>
      </section>

      <!-- 2. Board Setup -->
      <section class="document-section">
        <div class="section-header">
          <div class="section-number">2</div>
          <h2>Postflop Equity Distribution and Strategy Evaluation — At a Glance</h2>
        </div>
        <p class="section-intro">Turn community card information into actionable strategic insights.</p>
        
        <div class="feature-grid">
          <div class="feature-item">
            <h3>Flexible Board Setup & Statistics</h3>
            <ul>
              <li>Select any flop combination using interactive card grid with one-click random generation</li>
              <li>Real-time combo calculations: remaining combos, blocked by OOP, and flush/straight possibilities</li>
              <li>Enable Debug mode for advanced testing and solver validation</li>
            </ul>
          </div>
          
          <div class="feature-item">
            <h3>Board Strength Analysis</h3>
            <p>Comprehensive evaluation of board impact on ranges:</p>
            <ul>
              <li>Categorized from Very Low to Very High strength levels</li>
              <li>Compare OOP vs. IP coverage to highlight relative advantages and weaknesses</li>
              <li>Track opponent coverage effects on ranges in real-time</li>
            </ul>
          </div>
          
          <div class="feature-item">
            <h3>Equity Distribution Visualization</h3>
            <p>Clear visualization of equity across strength intervals:</p>
            <ul>
              <li>Divided into 0–20%, 20–40%, 40–60%, 60–80%, 80–100% ranges</li>
              <li>Instantly compare OOP vs. IP equity distribution at every level</li>
              <li>Quick identification of potential drawing possibilities and board dynamics</li>
            </ul>
          </div>
        </div>
        
        <div class="image-gallery">
          <img src="/Product_Website_Introduction/2-Board/board1.png" alt="Board Setup" />
        </div>
      </section>

      <!-- 3. Tree Configuration -->
      <section class="document-section">
        <div class="section-header">
          <div class="section-number">3</div>
          <h2>Comprehensive Customization from Stack Depth to Advanced Betting Rules</h2>
        </div>
        <p class="section-intro">Design your decision tree with full flexibility—from basic parameters to advanced logic—for complete control over strategy modeling.</p>
        
        <div class="feature-grid">
          <div class="feature-item">
            <h3>Basic Settings & Game Configuration</h3>
            <ul>
              <li>Starting Pot / Effective Stack simulation for different game depths and scenarios</li>
              <li>Rake (%) and Cap settings to recreate realistic playing conditions</li>
              <li>Save, load, rename, and group configurations with JSON import/export</li>
            </ul>
          </div>
          
          <div class="feature-item">
            <h3>Advanced Betting Logic Configuration</h3>
            <p>Define comprehensive betting and raising schemes for OOP and IP across all streets:</p>
            <ul>
              <li>Flexible Input: Supports percentages, multiples, geometric sizes, fixed raises, and all-ins</li>
              <li>Differentiated Setup: OOP can configure separate donk bet sizes</li>
              <li>Automation Rules: Apply all-in thresholds and merge similar bet sizes to simplify the tree</li>
            </ul>
          </div>
          
          <div class="feature-item">
            <h3>Advanced Features & Management</h3>
            <ul>
              <li>All-in Threshold: Automatically convert actions to all-in when SPR is low</li>
              <li>Bet Merging: Intelligently merge similar bet sizes to reduce redundant branches</li>
              <li>Debug Configuration: Instantly validate tree inputs and quickly switch between presets</li>
            </ul>
          </div>
        </div>
        
        <div class="image-gallery">
          <img src="/Product_Website_Introduction/3-Tree_Configuration/Tree_Configuration1.png" alt="Tree Configuration 1" />
          <img src="/Product_Website_Introduction/3-Tree_Configuration/Tree_Configuration2.png" alt="Tree Configuration 2" />
        </div>
      </section>

      <!-- 4. Bunching Effect -->
      <section class="document-section">
        <div class="section-header">
          <div class="section-number">4</div>
          <h2>Bringing Solvers Closer to Real Gameplay with Folded-Range Simulation</h2>
        </div>
        <p class="section-intro">A More Realistic Simulation - Introduce card removal effects from folded player ranges to make your analysis more accurate.</p>
        
        <div class="feature-grid">
          <div class="feature-item">
            <h3>What is the Bunching Effect?</h3>
            <p>In real games, most players fold weak hands, which means the remaining players are more likely to hold stronger ones. The Bunching Effect is designed to simulate this card-removal impact caused by folded ranges.</p>
          </div>
          
          <div class="feature-item">
            <h3>Key Features</h3>
            <ul>
              <li>Supports up to 4 folded players (ideal for 6-max scenarios)</li>
              <li>Enter folded player ranges and run a precomputation to account for the effect</li>
              <li>Exact simulation without abstractions or approximations, ensuring results that better reflect real gameplay</li>
            </ul>
          </div>
          
          <div class="feature-item warning">
            <h3>Important Notes</h3>
            <ul>
              <li>Enabling this option will significantly increase computation load and slow down the solver</li>
              <li>Recommended only when high-precision simulation is required; if unsure, leave it disabled</li>
            </ul>
          </div>
        </div>
        
        <div class="image-gallery">
          <img src="/Product_Website_Introduction/4-Bunching/Bunching1.png" alt="Bunching Effect" />
        </div>
      </section>

      <!-- 5. Run Solver -->
      <section class="document-section">
        <div class="section-header">
          <div class="section-number">5</div>
          <h2>Efficient Execution, Precise Control</h2>
        </div>
        <p class="section-intro">One-Click Solver Execution - Run the solver with a single click and generate optimal strategies efficiently.</p>
        
        <div class="feature-grid">
          <div class="feature-item">
            <h3>Configuration Options</h3>
            <ul>
              <li>Multi-threading Support: Adjust the number of threads based on your hardware to maximize performance</li>
              <li>Tree-Build Status: Real-time progress updates ensure correct input and successful setup</li>
              <li>Debug Mode: Quickly identify potential issues and improve tree-building efficiency</li>
            </ul>
          </div>
          
          <div class="feature-item">
            <h3>Calculation Settings</h3>
            <ul>
              <li>Precision Modes: Choose between 32-bit floating point (high precision) and 16-bit integer (lower memory usage)</li>
              <li>Target Exploitability: Set a precision threshold (e.g., 0.3%) to guarantee strategy quality</li>
              <li>Iteration Control: Define maximum iterations to balance speed and accuracy</li>
            </ul>
          </div>
          
          <div class="feature-item">
            <h3>Execution & Control</h3>
            <ul>
              <li>Run Solver: Start solving instantly with one click</li>
              <li>Stop / Pause: Interrupt or pause calculations anytime for flexible control</li>
            </ul>
          </div>
        </div>
        
        <div class="image-gallery">
          <img src="/Product_Website_Introduction/5-Run_Solver/Run_Solver1.png" alt="Run Solver" />
        </div>
      </section>

      <!-- 6. File Operations -->
      <section class="document-section">
        <div class="section-header">
          <div class="section-number">6</div>
          <h2>One-Click Reuse of Configurations and Results</h2>
        </div>
        <p class="section-intro">Effortlessly Save and Load - Easily save and load solver configurations and results to streamline your workflow.</p>
        
        <div class="feature-grid">
          <div class="feature-item">
            <h3>Save & Load Configurations</h3>
            <ul>
              <li>Save Configuration: Store all current settings (board setup, ranges, game tree, etc.) as a JSON file for future reuse</li>
              <li>Load Configuration: Instantly load all settings from a previously saved JSON file to quickly restore your environment</li>
            </ul>
          </div>
          
          <div class="feature-item">
            <h3>Save & Load Solutions</h3>
            <ul>
              <li>Save Solution: Save completed solver results as a binary file for fast access later</li>
              <li>Load Solution: Reload previously saved solver results without recalculation</li>
            </ul>
          </div>
        </div>
        
        <div class="image-gallery">
          <img src="/Product_Website_Introduction/6-File_Operations/File_Operations1.png" alt="File Operations" />
        </div>
      </section>

      <!-- 7. Results Classic -->
      <section class="document-section">
        <div class="section-header">
          <div class="section-number">7</div>
          <h2>Comprehensive Strategy Insights with Interactive Tables and Multi-Dimensional Views</h2>
        </div>
        <p class="section-intro">Interactive Result Display - Gain a clear understanding of strategy details at a glance with fully interactive result visualization.</p>
        
        <div class="feature-grid">
          <div class="feature-item">
            <h3>Summary Table & View Switching</h3>
            <p>A Display dropdown menu above the Summary table allows you to seamlessly switch between different data dimensions:</p>
            <ul>
              <li>Strategy: Optimal strategy distribution</li>
              <li>Strategy + EQ / EV / EQR: Overlay equity, expected value (EV), or equilibrium ratio (EQR) on top of strategy</li>
              <li>Weight / EQ / EV / EQR: Independently view hand weight, equity, expected value, or equilibrium ratio</li>
            </ul>
            <p>This integrated design lets you explore multiple analytical perspectives within the same table, eliminating the need to switch views elsewhere.</p>
          </div>
          
          <div class="feature-item">
            <h3>Comprehensive Data Overview</h3>
            <p>For each hand, the table provides:</p>
            <ul>
              <li>Strategy distribution</li>
              <li>Hand weight</li>
              <li>Equity (EQ)</li>
              <li>Expected value (EV)</li>
              <li>Equilibrium ratio (EQR)</li>
            </ul>
            <p>A Total row is also included, making it easy to compare overall OOP vs. IP performance at a glance.</p>
          </div>
          
          <div class="feature-item">
            <h3>Debugging & Decision Paths</h3>
            <ul>
              <li>Debug: Quickly identify unusual strategies or specific nodes</li>
              <li>Decision Path: Trace the full sequence of actions to understand the logic behind every decision.</li>
            </ul>
            <p><em>Note: Decision Path displays JSON-format decision data only. If you want to save or share solver configurations or solver results, you still need to use File Operations to export them as JSON or BIN files.</em></p>
          </div>
        </div>
        
        <div class="image-gallery">
          <img src="/Product_Website_Introduction/7-Results_Classic/Results_Classic1.png" alt="Results Classic" />
        </div>
      </section>

      <!-- 8. Results Pro -->
      <section class="document-section">
        <div class="section-header">
          <div class="section-number">8</div>
          <h2>Professional Enhanced Results Viewer – Multi-Tab Support for Analyzing Multiple Opponents</h2>
        </div>
        <p class="section-intro">All Classic Features Retained - Includes everything from the Classic version: Summary table, Heatmap, Graphs, and Compare mode.</p>
        
        <div class="feature-grid">
          <div class="feature-item">
            <h3>Multi-Tab Design</h3>
            <p>Unlike the Classic version, which analyzes a single opponent at a time, the Pro version supports multiple tabs:</p>
            <ul>
              <li>In the same hand, view your strategy against multiple positions simultaneously (e.g., BTN vs SB & BB & MP & CO)</li>
              <li>Instantly switch between tabs to compare how different opponents respond</li>
              <li>Better reflects real in-game scenarios, making reviews and coaching more efficient</li>
            </ul>
          </div>
        </div>
        
        <div class="image-gallery">
          <img src="/Product_Website_Introduction/8-Results_Pro/Results_Pro1.png" alt="Results Pro" />
        </div>
      </section>
    </div>
  </div>
</template>

<script setup>
// 下载按钮点击事件
const handleDownload = (platform) => {
  // 这里可以添加实际的下载逻辑
  console.log(`Downloading for ${platform}`);
  
  // 示例：可以跳转到实际的下载链接
  // window.open(`https://example.com/download/${platform}`, '_blank');
  
  // 或者显示下载提示
  alert(`Download for ${platform} - This would normally start the download process.`);
}

// 为每个按钮添加点击事件
const downloadWindows = () => handleDownload('Windows');
const downloadMac = () => handleDownload('Mac');
const downloadLinux = () => handleDownload('Linux');
</script>

<style scoped>
.home {
  width: 100vw;
  min-height: 100vh;
  background: #f8f9fa;
  margin: 0;
  padding: 0;
}

.hero {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  margin-bottom: 0;
}

.hero h1 {
  font-size: 3.5rem;
  margin-bottom: 1rem;
  font-weight: 700;
}

.subtitle {
  font-size: 1.8rem;
  margin-bottom: 0.5rem;
  opacity: 0.9;
}

.description {
  font-size: 1.2rem;
  opacity: 0.8;
  margin-bottom: 2rem;
}

.download-section {
  margin-top: 2rem;
  padding: 2rem;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 12px;
  backdrop-filter: blur(10px);
  position: relative;
}

.free-badge {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
  background: linear-gradient(135deg, #4CAF50 0%, #45a049 100%);
  color: white;
  padding: 0.75rem 1.5rem;
  border-radius: 25px;
  font-weight: 700;
  font-size: 1.1rem;
  margin-bottom: 1.5rem;
  box-shadow: 0 4px 15px rgba(76, 175, 80, 0.3);
  animation: pulse 2s infinite;
  border: 2px solid rgba(255, 255, 255, 0.2);
}

.free-icon {
  font-size: 1.3rem;
  animation: bounce 1s infinite alternate;
}

.free-text {
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.2);
}

@keyframes pulse {
  0% {
    box-shadow: 0 4px 15px rgba(76, 175, 80, 0.3);
  }
  50% {
    box-shadow: 0 4px 25px rgba(76, 175, 80, 0.5);
  }
  100% {
    box-shadow: 0 4px 15px rgba(76, 175, 80, 0.3);
  }
}

@keyframes bounce {
  0% {
    transform: translateY(0);
  }
  100% {
    transform: translateY(-3px);
  }
}

.download-section h3 {
  margin: 0 0 1.5rem 0;
  font-size: 1.5rem;
  font-weight: 600;
  color: white;
  text-align: center;
}

.download-buttons {
  display: flex;
  justify-content: center;
  gap: 1.5rem;
  flex-wrap: wrap;
}

.download-btn {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  padding: 1rem 2rem;
  background: rgba(255, 255, 255, 0.9);
  color: #333;
  border: none;
  border-radius: 8px;
  font-size: 1rem;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s ease;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  min-width: 180px;
  justify-content: center;
}

.download-btn:hover {
  background: white;
  transform: translateY(-2px);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

.download-btn:active {
  transform: translateY(0);
}

.download-icon {
  width: 20px;
  height: 20px;
  flex-shrink: 0;
}

.download-btn.windows:hover {
  background: #0078d4;
  color: white;
}

.download-btn.mac:hover {
  background: #0071e3;
  color: white;
}

.download-btn.linux:hover {
  background: #fcc624;
  color: #333;
}

.content {
  width: 100%;
  padding: 0 2rem;
}

.document-section {
  background: white;
  margin: 2rem 0;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  overflow: hidden;
}

.section-header {
  display: flex;
  align-items: center;
  padding: 2rem;
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  border-bottom: 1px solid #e9ecef;
}

.section-number {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 60px;
  height: 60px;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  border-radius: 50%;
  font-weight: bold;
  font-size: 1.5rem;
  margin-right: 2rem;
  flex-shrink: 0;
}

.section-header h2 {
  margin: 0;
  font-size: 2rem;
  color: #333;
  line-height: 1.2;
}

.section-intro {
  padding: 2rem;
  font-size: 1.1rem;
  color: #555;
  line-height: 1.6;
  margin: 0;
  background: #f8f9fa;
  border-bottom: 1px solid #e9ecef;
}

.feature-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  padding: 2rem;
}

.feature-item {
  padding: 1.5rem;
  background: #f8f9fa;
  border-radius: 8px;
  border-left: 4px solid #667eea;
}

.feature-item.warning {
  background: #fff3cd;
  border-left-color: #ffc107;
}

.feature-item h3 {
  margin: 0 0 1rem 0;
  font-size: 1.3rem;
  color: #333;
}

.feature-item p {
  margin: 0 0 1rem 0;
  color: #555;
  line-height: 1.5;
}

.feature-item ul {
  margin: 0;
  padding-left: 1.5rem;
  color: #555;
}

.feature-item li {
  margin-bottom: 0.5rem;
  line-height: 1.4;
}

.image-gallery {
  padding: 2rem;
  text-align: center;
  background: #f8f9fa;
  border-top: 1px solid #e9ecef;
}

.image-gallery img {
  max-width: 100%;
  height: auto;
  margin: 1rem;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

@media (max-width: 768px) {
  .hero h1 {
    font-size: 2.5rem;
  }
  
  .subtitle {
    font-size: 1.4rem;
  }
  
  .description {
    font-size: 1rem;
  }
  
  .download-section {
    padding: 1.5rem;
    margin-top: 1.5rem;
  }
  
  .free-badge {
    padding: 0.6rem 1.2rem;
    font-size: 1rem;
    margin-bottom: 1.2rem;
  }
  
  .free-icon {
    font-size: 1.1rem;
  }
  
  .download-buttons {
    flex-direction: column;
    align-items: center;
    gap: 1rem;
  }
  
  .download-btn {
    min-width: 200px;
    width: 100%;
    max-width: 250px;
  }
  
  .section-header {
    flex-direction: column;
    text-align: center;
  }
  
  .section-number {
    margin-right: 0;
    margin-bottom: 1rem;
  }
  
  .section-header h2 {
    font-size: 1.5rem;
  }
  
  .feature-grid {
    grid-template-columns: 1fr;
    padding: 1rem;
  }
  
  .content {
    padding: 0 1rem;
  }
}
</style>
