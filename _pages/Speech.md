---
permalink: /Speech/
redirect_from:
  - /resume
---

{% include base_path %}
<div class="speech-container">
    <h1>Keynote / Invited Speech</h1>
    <div class="speeches">
        <div class="speech-column">
            <h2>2020</h2>
            <ul>
                <li><a href="talk1-1/">Prof. Han Huang: 从微搜索假设看进化计算方法</a></li>
                <li><a href="talk1-2/">Prof. Bin Xin: Aerial-Surface Cooperation of Heterogeneous Unmanned Vehicles in Complex Missions</a></li>
                <li><a href="talk1-3/">Prof. Xiaomin Zhu: Aggregation and emergence of swarm based on the evolution mechanism of organism</a></li>
                <li><a href="talk1-4/">Prof. Dunwei Gong: 进化优化与知识共融的软件变异测试</a></li>
                <li><a href="talk1-5/">Prof. Leonid Alekseevich Ivanov: To Be Confirmed</a></li>
                <li><a href="talk1-6/">Prof. Qingfu Zhang: 启发性算法设计的几个问题</a></li>
                <li><a href="talk1-7/">Prof. Shane Xie: Innovative Robotic Technology and Artificial Intelligence for the Future of Healthcare</a></li>
                <li><a href="talk1-8/">Prof. Shengxiang Yang: Swarm Intelligence for Dynamic Optimization Problems</a></li>
                <li><a href="talk1-9/">Prof. Yaochu Jin: Communication-efficient federated learning</a></li>
                <li><a href="talk1-10/">Prof. Weihua Shen: ASCCBot: A Robotic Assistant for the Home Healthcare Industry</a></li>
                <li><a href="talk1-11/">Prof. Yantao Shen: Adaptive Path Following of Underactuated Biomimetic Snake Robots</a></li>
                <li><a href="talk1-12/">Prof. Kangshun Li: 基于适应度景观的差分进化算法变异算子及参数选择研究</a></li>
                <li><a href="talk1-13/">Prof. Shiping Wen: Memristor-based Neuromorphic Computing Systems</a></li>
                <li><a href="talk1-14/">Prof. Ke Tang: Scalable Evolutionary Search</a></li>
                <li><a href="talk1-15/">Prof. Hailin Liu: Evolutionary Multi- and Many-Objective Optimization Algorithm Using Region Decomposition</a></li>
                <li><a href="talk1-16/">Prof. Hui Li: On the population strategies in MOEA/D</a></li>
                <li><a href="talk1-17/">Prof. Xinye Cai: 面向航空领域的智能优化方法与应用</a></li>
                <li><a href="talk1-18/">Prof. Lijie Li: Strain modulated nanomaterials with applications electronic and photonic systems</a></li>
                <li><a href="talk1-19/">Prof. Menglun Tao: Smart materials and actuators for ultrasonic assisted machining and micro/nano positioning</a></li>
                <li><a href="talk1-20/">Prof. Haibin Zhu: From Group Role Assignment (GRA) to GRA with Constraints (GRA+) and GRA with Multiple Objectives (GRA++)</a></li>
                <li><a href="talk1-21/">Prof. Heping Chen: Intelligent Manufacturing Processes Using Industrial Robots</a></li>
                <li><a href="talk1-22/">Prof. Yiping Liu: Handling imbalance between convergence and diversity in the decision space in evolutionary multi-modal multi-objective optimization</a></li>
                <li><a href="talk1-23/">Prof. Zhenyuan Liu: A Simulation-based Method for Designing Parameters of Material Price Adjustment Model in Large-scale Hydropower Development in China</a></li>
                <li><a href="talk1-24/">Prof. Kun Liu: Security and privacy of cyber-physical systems</a></li>
                <li><a href="talk1-25/">Prof. Jie Mei: Simulation and experiment for Doubly-clamped Flexible Piezoelectric Energy Harvester</a></li>
                <li><a href="talk1-26/">Prof. Jiang Wu: Can functional materials enhance the practicality of ultrasonic motors? A trial investigation</a></li>
                <li><a href="talk1-27/">Prof. Zhijun Zhang: Vary Parameter Recurrent Neural Network Applied to Intelligent Robots and Data Analysis</a></li>
                <li><a href="talk1-28/">Prof. Miroslav Joler: Challenges Toward Design and Fabrication of Smart(er) Clothing</a></li>
                <li><a href="talk1-29/">Prof. Alex Noel Joseph Raj: Hybrid U-NET models for lesion segmentation in Medical Images</a></li>
            </ul>
        </div>
    </div>
</div>

<style>
  
.speeches {
    display: flex;
    flex-wrap: wrap;
    justify-content: center; /* 使所有列居中对齐 */
    gap: 20px; /* 每列之间的间距 */
}

.speech-column {
    width: 50%; /* 设置每列宽度为 22%，以便能够容纳四列，并留出间隙 */
    box-sizing: border-box; /* 确保 padding 和 border 不影响整体宽度 */
    padding: 10px;
    background-color: #f9f9f9; /* 给每列添加背景色，使它们更明显 */
    text-align: center; /* 每列内文本居中 */
}

.speech-column h2 {
    font-size: 1.2em; /* 调整标题大小 */
    color: #2c3e50; /* 设置标题颜色 */
    margin-bottom: 12px; /* 与列表之间的间距 */
    text-align: center;
}

.speech-column ul {
    list-style-type: none;
    padding: 0;
}

.speech-column li {
    margin: 15px 0;
    padding: 20px;
    background-color: #f1f1f1;
    border: 1px solid #ddd;
    border-radius: 5px;
    height: 200px; /* 设置固定高度，确保每个框的大小一致 */
    display: flex;
    align-items: center; /* 使文字在框内垂直居中 */
    transition: transform 0.3s, box-shadow 0.3s;
}

.speech-column li:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
}

.speech-column li a {
    text-decoration: none;
    color: #2980b9;
    font-weight: bold;
    text-align: center; /* 链接文字居中 */
    width: 100%;
}

.speech-column li a:hover {
    text-decoration: underline;
}


.speech-container {
    position: relative; /* 可选：如果不想保持相对定位，删除这行 */
    width: 100vw; /* 删除这一行，使容器不再强制占满整个视口宽度 */
    margin-left: calc(50% - 50vw); /* 删除这一行，取消强制容器宽度从页面边界开始 */
    padding: 30px;
    background-color: #ffffff;
    border-radius: 10px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

.speech-container h1 {
    font-size: 2em;
    color: #2c3e50;
    margin-bottom: 20px;
    text-align: center;
    position: sticky; /* 保持标题在页面顶部可见 */
    top: 0;
    background-color: #ffffff;
    padding: 20px;
    z-index: 10;
}
  
</style>
