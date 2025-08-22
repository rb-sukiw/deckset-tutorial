---
theme: neversink
title: Network Analysis in Organizations
info: |
  ## Network Analysis in Organizations
  Effectiveness & Leadership Potential Studies

  Understanding the hidden networks that drive organizational success.
author: Your Name
organization: Roblox
class: text-center
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true
fonts:
  sans: Roboto
  mono: Fira Code
colorSchema: auto
themeConfig:
  primary: "#00A2FF"
  secondary: "#00D924"
  accent: "#FFA500"
  background: "#0f172a"
  text: "#f8fafc"
---

<style>
.roblox-header {
  position: fixed;
  top: 20px;
  right: 20px;
  display: flex;
  align-items: center;
  gap: 10px;
  z-index: 1000;
  background: rgba(255, 255, 255, 0.95);
  padding: 8px 12px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.roblox-logo {
  width: 32px;
  height: 32px;
  background: #00A2FF;
  border-radius: 6px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-weight: bold;
  font-size: 16px;
}

.viz-placeholder {
  border: 2px dashed #4a5568;
  border-radius: 12px;
  background: rgba(74, 85, 104, 0.1);
  display: flex;
  align-items: center;
  justify-content: center;
  color: #4a5568;
  font-style: italic;
  min-height: 200px;
}

.animated-placeholder {
  border: 2px dashed #00A2FF;
  border-radius: 12px;
  background: rgba(0, 162, 255, 0.1);
  display: flex;
  align-items: center;
  justify-content: center;
  color: #00A2FF;
  font-style: italic;
  min-height: 150px;
  animation: pulse 2s infinite;
}

@keyframes pulse {
  0%, 100% { opacity: 0.5; }
  50% { opacity: 1; }
}

.network-animation {
  width: 100%;
  height: 300px;
  background: linear-gradient(45deg, #00A2FF20, #00D92420);
  border-radius: 12px;
  position: relative;
  overflow: hidden;
}

.network-animation::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
  animation: shimmer 3s infinite;
}

@keyframes shimmer {
  0% { left: -100%; }
  100% { left: 100%; }
}
</style>

<div class="flex justify-center mb-6">
  <div class="text-8xl">🕸️</div>
</div>

# Network Analysis in Organizations

by **Your Name** • *Your Organization*

:: note ::

\* Effectiveness & Leadership Potential Studies

<!--
Today we'll explore:
- What organizational network analysis is and why it matters
- How to identify hidden leadership potential through network positions
- Practical applications for talent development and organizational design
- Tools and methods for conducting network analysis
- Real-world case studies and insights
-->

---
layout: top-title
color: sky-light
align: c
---

:: title ::

# 🎯 What We'll Discover

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div>
    <div class="text-4xl mb-3">🔍</div>
    <div class="text-xl mb-2">Hidden Networks</div>
    <div class="text-sm text-gray-600">Revealing informal structures that drive performance</div>
  </div>
  <div>
    <div class="text-4xl mb-3">👥</div>
    <div class="text-xl mb-2">Leadership Potential</div>
    <div class="text-sm text-gray-600">Identifying future leaders through network positions</div>
  </div>
  <div>
    <div class="text-4xl mb-3">⚡</div>
    <div class="text-xl mb-2">Team Effectiveness</div>
    <div class="text-sm text-gray-600">Optimizing collaboration and knowledge flow</div>
  </div>
  <div>
    <div class="text-4xl mb-3">🎯</div>
    <div class="text-xl mb-2">Practical Tools</div>
    <div class="text-sm text-gray-600">Real-world applications and methodologies</div>
  </div>
</div>

---
layout: top-title
color: emerald-light
align: c
---

:: title ::

# What is Network Analysis?

:: content ::

<div class="text-center">
  <div class="text-6xl mb-8 mt-8">
    👥 + 🔗 + 📊 = 🚀
  </div>

  <div class="text-2xl text-gray-600">
    People + Relationships + Data = Insights
  </div>
</div>

<!--
Network analysis is the study of relationships and interactions within organizations:

It's fundamentally different from traditional HR approaches:
- Instead of individual assessments, we examine relationships
- Instead of formal hierarchies, we map informal influence
- Instead of static roles, we track dynamic interactions
- Instead of assumptions, we use data-driven insights

Network analysis reveals:
- Who really influences decisions
- How information flows through the organization
- Which employees are critical connectors
- Where bottlenecks and silos exist
- How teams actually collaborate vs. how they're supposed to
-->

---
layout: two-cols-title
columns: is-6
align: c-lt-lt
color: sky-light
---

:: title ::

# Traditional vs Network View

:: left ::

## 📊 Traditional Approach

- Formal org charts
- Individual performance metrics
- Position-based authority
- Standardized assessments

:: right ::

## 🕸️ Network Approach

- Relationship maps
- Influence patterns
- Informal leadership
- Collaborative behaviors

<!--
The contrast is striking:

Traditional HR relies on:
- Formal reporting structures that may not reflect reality
- Individual KPIs that miss collaborative contributions
- Job titles that may not indicate actual influence
- Annual reviews that capture a snapshot in time

Network analysis reveals:
- Who people actually go to for advice and support
- How influence flows regardless of hierarchy
- Which employees serve as bridges between groups
- How collaboration patterns predict team success
- Where the real decision-making happens

This shift from individual to relational thinking transforms how we understand organizational effectiveness.
-->

---
layout: top-title
color: indigo-light
align: c
---

:: title ::

# Key Network Metrics

:: content ::

<div class="grid grid-cols-2 gap-6 mt-4">
  <div class="text-center">
    <div class="text-3xl mb-2 text-blue-400">🎯</div>
    <div class="text-lg font-semibold">Degree Centrality</div>
    <div class="text-sm text-gray-600">Number of direct connections</div>
  </div>
  <div class="text-center">
    <div class="text-3xl mb-2 text-green-400">🌉</div>
    <div class="text-lg font-semibold">Betweenness Centrality</div>
    <div class="text-sm text-gray-600">Bridge between groups</div>
  </div>
  <div class="text-center">
    <div class="text-3xl mb-2 text-purple-400">⚡</div>
    <div class="text-lg font-semibold">Closeness Centrality</div>
    <div class="text-sm text-gray-600">Speed of information access</div>
  </div>
  <div class="text-center">
    <div class="text-3xl mb-2 text-orange-400">⭐</div>
    <div class="text-lg font-semibold">Eigenvector Centrality</div>
    <div class="text-sm text-gray-600">Connected to important people</div>
  </div>
</div>

<div class="mt-6 text-center text-lg text-gray-600">
  Each metric reveals different aspects of network position and influence
</div>

---
layout: top-title
color: amber-light
align: c
---

:: title ::

# 🌟 Leadership Potential Indicators

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div>
    <div class="text-4xl mb-3">🌉</div>
    <div class="text-xl mb-2 font-semibold">Bridge Builders</div>
    <div class="text-base text-gray-600">High betweenness centrality indicates natural connectors who facilitate communication across groups</div>
  </div>
  <div>
    <div class="text-4xl mb-3">📈</div>
    <div class="text-xl mb-2 font-semibold">Growing Influence</div>
    <div class="text-base text-gray-600">Expanding network reach over time shows developing leadership capacity</div>
  </div>
  <div>
    <div class="text-4xl mb-3">🔄</div>
    <div class="text-xl mb-2 font-semibold">Boundary Spanners</div>
    <div class="text-base text-gray-600">Cross-functional connections demonstrate ability to break down silos</div>
  </div>
  <div>
    <div class="text-4xl mb-3">💡</div>
    <div class="text-xl mb-2 font-semibold">Knowledge Brokers</div>
    <div class="text-base text-gray-600">Access to diverse information sources enables innovation and problem-solving</div>
  </div>
</div>

---
layout: top-title
align: c
---

:: title ::

# 📊 Data Collection Methods

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div class="bg-blue-50 p-6 rounded-lg">
    <div class="text-xl font-bold text-blue-800 mb-3">🗣️ Meetings </div>
    <div class="text-blue-700 text-sm space-y-2">
      <div>• 1 on 1 Connections</div>
      <div>• Manager Upward Meetings?</div>
      <div>• Team Meetings</div>
      <div>• Project Collaborations</div>
    </div>
  </div>
  <div class="bg-green-50 p-6 rounded-lg">
    <div class="text-xl font-bold text-green-800 mb-3">💻 Peer Feedback</div>
    <div class="text-green-700 text-sm space-y-2">
      <div>• "Who you collaborated with in the last cycle?"</div>
      <div>• "Who provided feedback for you in the past?"</div>
      <div>• "Who you provided feedback to?"</div>
      <div>• Feedback Pillars</div>
    </div>
  </div>
</div>


<div class="mt-6 text-center text-lg text-gray-600">
  Combine multiple data sources for comprehensive network mapping
</div>

---
layout: top-title
align: c
---

:: title ::

# 🏢 Identify Informal Influencers

:: content ::

<div class="text-center">
<div class="text-6xl mb-4">📈</div>
<div class="text-2xl mb-4 font-semibold">The Bridge Builder Effect</div>
</div>

<div class="bg-blue-50 p-6 rounded-lg mt-4">
  <div class="text-blue-800 text-xl font-bold mb-3">🔍 Key Finding</div>
  <div class="text-blue-700 text-lg">
    Employees with high betweenness centrality were <strong>3x more likely</strong> to be promoted to leadership roles within 2 years
  </div>
</div>

<div class="grid grid-cols-3 gap-4 mt-6">
  <div class="text-center">
    <div class="text-3xl mb-1">⚡</div>
    <div class="text-sm">Faster problem-solving</div>
  </div>
  <div class="text-center">
    <div class="text-3xl mb-1">🤝</div>
    <div class="text-sm">Better collaboration</div>
  </div>
  <div class="text-center">
    <div class="text-3xl mb-1">💡</div>
    <div class="text-sm">Increased innovation</div>
  </div>
</div>

---
layout: top-title-two-cols
align: c-lt-lt
columns: is-6
---

:: title ::

# 🎯 Practical Applications

:: left ::

<div class="bg-green-100 p-6 rounded-lg mb-6">
  <div class="text-xl font-bold text-green-800 mb-2">👥 Talent Development</div>
  <div class="text-green-700 text-sm">
    • Identify high-potential leaders early<br>
    • Create targeted mentorship programs<br>
    • Build succession planning strategies<br>
    • Design leadership development paths
  </div>
</div>

<div class="bg-purple-100 p-6 rounded-lg">
  <div class="text-xl font-bold text-purple-800 mb-2">🎪 Team Formation</div>
  <div class="text-purple-700 text-sm">
    • Optimize project team composition<br>
    • Balance connectivity and diversity<br>
    • Ensure knowledge flow paths<br>
    • Minimize communication bottlenecks
  </div>
</div>

:: right ::

<div class="bg-blue-100 p-6 rounded-lg mb-6">
  <div class="text-xl font-bold text-blue-800 mb-2">🏗️ Organizational Design</div>
  <div class="text-blue-700 text-sm">
    • Optimize team structures<br>
    • Improve information flow<br>
    • Reduce silos and bottlenecks<br>
    • Enhance cross-functional collaboration
  </div>
</div>

<div class="bg-orange-100 p-6 rounded-lg">
  <div class="text-xl font-bold text-orange-800 mb-2">📊 Change Management</div>
  <div class="text-orange-700 text-sm">
    • Identify key influencers<br>
    • Design communication strategies<br>
    • Monitor adoption patterns<br>
    • Accelerate organizational transformation
  </div>
</div>

---
layout: top-title
align: c
---

:: title ::

# 🛠️ Implementation Framework

:: content ::

<div class="text-4xl mb-6 text-center">🗺️ → 📊 → 🔍 → 🎯 → 📈</div>

<div class="grid grid-cols-5 gap-4 mt-6">
  <div class="text-center">
    <div class="text-3xl mb-2">🗺️</div>
    <div class="text-sm font-semibold">Network Mapping</div>
    <div class="text-xs text-gray-600">Collect relationship data</div>
  </div>
  <div class="text-center">
    <div class="text-3xl mb-2">📊</div>
    <div class="text-sm font-semibold">Metric Calculation</div>
    <div class="text-xs text-gray-600">Compute centrality measures</div>
  </div>
  <div class="text-center">
    <div class="text-3xl mb-2">🔍</div>
    <div class="text-sm font-semibold">Pattern Analysis</div>
    <div class="text-xs text-gray-600">Identify key insights</div>
  </div>
  <div class="text-center">
    <div class="text-3xl mb-2">🎯</div>
    <div class="text-sm font-semibold">Intervention Design</div>
    <div class="text-xs text-gray-600">Create targeted programs</div>
  </div>
  <div class="text-center">
    <div class="text-3xl mb-2">📈</div>
    <div class="text-sm font-semibold">Impact Assessment</div>
    <div class="text-xs text-gray-600">Measure improvements</div>
  </div>
</div>

---
layout: top-title
color: red-light
align: c
---

:: title ::

# ⚠️ Challenges & Considerations

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div class="bg-red-50 p-6 rounded-lg">
    <div class="text-red-700 font-bold mb-3 text-lg">🔒 Privacy & Ethics</div>
    <div class="text-base text-red-600">
      • Ensure data anonymization<br>
      • Obtain informed consent<br>
      • Transparent communication<br>
      • Respect individual boundaries
    </div>
  </div>
  <div class="bg-yellow-50 p-6 rounded-lg">
    <div class="text-yellow-700 font-bold mb-3 text-lg">🔄 Dynamic Nature</div>
    <div class="text-base text-yellow-600">
      • Networks constantly evolve<br>
      • Regular measurement needed<br>
      • Context-dependent patterns<br>
      • Cultural influences matter
    </div>
  </div>
</div>

<div class="mt-6 text-center text-lg text-gray-600">
  Success requires careful attention to ethical considerations and measurement validity
</div>

---
layout: top-title
color: blue-light
align: c
---

:: title ::

# 📈 Research Impact

:: content ::

<div class="text-center mb-8">
  <div class="text-6xl mb-4">🎯</div>
  <div class="text-2xl font-semibold">Organizations using network analysis show:</div>
</div>

<div class="grid grid-cols-3 gap-6">
  <div class="text-center bg-green-50 p-6 rounded-lg">
    <div class="text-4xl font-bold text-green-600 mb-2">25%</div>
    <div class="text-lg text-green-700">Improvement in succession planning accuracy</div>
  </div>
  <div class="text-center bg-blue-50 p-6 rounded-lg">
    <div class="text-4xl font-bold text-blue-600 mb-2">30%</div>
    <div class="text-lg text-blue-700">Reduction in time-to-leadership readiness</div>
  </div>
  <div class="text-center bg-purple-50 p-6 rounded-lg">
    <div class="text-4xl font-bold text-purple-600 mb-2">40%</div>
    <div class="text-lg text-purple-700">Increase in cross-functional collaboration</div>
  </div>
</div>

---
layout: top-title-two-cols
align: c-lt-lt
columns: is-6
---

:: title ::

# 🛠️ Tools & Technologies

:: left ::

<div class="bg-blue-100 p-6 rounded-lg mb-6">
  <div class="text-xl font-bold text-blue-800 mb-2">📊 Analysis Software</div>
  <div class="text-blue-700 text-sm">
    • <strong>Gephi</strong> → Network visualization<br>
    • <strong>NetworkX</strong> → Python-based analysis<br>
    • <strong>OrgMapper</strong> → Enterprise solutions<br>
    • <strong>Polinode</strong> → Survey-based mapping
  </div>
</div>

:: right ::

<div class="bg-green-100 p-6 rounded-lg mb-6">
  <div class="text-xl font-bold text-green-800 mb-2">📡 Data Sources</div>
  <div class="text-green-700 text-sm">
    • Communication platforms (Slack, Teams)<br>
    • Email metadata and patterns<br>
    • Survey responses and assessments<br>
    • Meeting and collaboration records
  </div>
</div>

<div class="mt-6 text-center text-lg text-gray-600">
  Choose tools based on data sources, analysis needs, and organizational context
</div>

---
layout: top-title
color: purple-light
align: c
---

:: title ::

# 🚀 Future Directions

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div>
    <div class="text-4xl mb-3">🤖</div>
    <div class="text-xl mb-2 font-semibold">AI-Powered Prediction</div>
    <div class="text-base text-gray-600">Machine learning models predict network evolution and leadership emergence</div>
  </div>
  <div>
    <div class="text-4xl mb-3">⚡</div>
    <div class="text-xl mb-2 font-semibold">Real-Time Monitoring</div>
    <div class="text-base text-gray-600">Continuous tracking of network changes and organizational dynamics</div>
  </div>
  <div>
    <div class="text-4xl mb-3">🏗️</div>
    <div class="text-xl mb-2 font-semibold">Multi-Layer Analysis</div>
    <div class="text-base text-gray-600">Simultaneous analysis of multiple relationship types and contexts</div>
  </div>
  <div>
    <div class="text-4xl mb-3">📊</div>
    <div class="text-xl mb-2 font-semibold">Performance Integration</div>
    <div class="text-base text-gray-600">Linking network positions directly to business outcomes and KPIs</div>
  </div>
</div>

---
layout: top-title
align: c
---

:: title ::

# 🎯 Key Takeaways

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div class="text-center">
    <div class="text-4xl mb-3">🔍</div>
    <div class="text-lg mb-2 font-semibold">Hidden Talent Revealed</div>
    <div class="text-sm text-gray-600">Networks expose leadership potential missed by traditional assessments</div>
  </div>
  <div class="text-center">
    <div class="text-4xl mb-3">🌉</div>
    <div class="text-lg mb-2 font-semibold">Bridge Positions Matter</div>
    <div class="text-sm text-gray-600">Connector roles predict success better than individual traits alone</div>
  </div>
  <div class="text-center">
    <div class="text-4xl mb-3">⚖️</div>
    <div class="text-lg mb-2 font-semibold">Balance is Key</div>
    <div class="text-sm text-gray-600">Effective organizations optimize connection density with strategic bridges</div>
  </div>
  <div class="text-center">
    <div class="text-4xl mb-3">📊</div>
    <div class="text-lg mb-2 font-semibold">Data-Driven ROI</div>
    <div class="text-sm text-gray-600">Network-based approaches significantly improve leadership development outcomes</div>
  </div>
</div>

---
layout: center
class: text-center
---

# Questions & Discussion

<div class="text-6xl mb-8">🤔</div>

## Contact Information
**Your Name**  
`your.email@organization.com`

<div class="text-xl italic mt-8 text-gray-600">
"The future belongs to organizations that can map, understand, and optimize their human networks."
</div>

---
layout: top-title
---

:: title ::

# 📚 References & Further Reading

:: content ::

<div class="text-lg space-y-3 mt-6">
  <div>• Borgatti, S.P. & Foster, P.C. (2003). The network paradigm in organizational research</div>
  <div>• Cross, R. & Parker, A. (2004). The Hidden Power of Social Networks</div>
  <div>• Brass, D.J. (1984). Being in the right place: A structural analysis of individual influence</div>
  <div>• Burt, R.S. (2005). Brokerage and Closure: An Introduction to Social Capital</div>
  <div>• Wasserman, S. & Faust, K. (1994). Social Network Analysis: Methods and Applications</div>
</div>

---
layout: center
class: text-center
---

# Thank You

<div class="text-6xl mb-8">🙏</div>

<div class="pt-8">
  <span class="px-4 py-2 rounded cursor-pointer text-lg" hover="bg-white bg-opacity-10">
    Let's unlock the power of organizational networks! 🚀
  </span>
</div>