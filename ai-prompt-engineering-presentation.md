---
theme: neversink
title: AI & Prompt Engineering for Graduate Students
info: |
  ## AI & Prompt Engineering for Graduate Students
  3-Week Intensive Course
  
  Mastering the art and science of human-AI collaboration.
author: Your Name
organization: University
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
  primary: "#FF6B6B"
  secondary: "#4ECDC4" 
  accent: "#45B7D1"
  background: "#0f172a"
  text: "#f8fafc"
---

<style>
.university-header {
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

.university-logo {
  width: 32px;
  height: 32px;
  background: #FF6B6B;
  border-radius: 6px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-weight: bold;
  font-size: 16px;
}

.gradient-text {
  background: linear-gradient(135deg, #FF6B6B, #4ECDC4, #45B7D1);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.brain-animation {
  width: 100%;
  height: 200px;
  background: linear-gradient(45deg, #FF6B6B20, #4ECDC420);
  border-radius: 12px;
  position: relative;
  overflow: hidden;
  animation: pulse 3s ease-in-out infinite;
}

@keyframes pulse {
  0%, 100% { transform: scale(1); opacity: 0.8; }
  50% { transform: scale(1.05); opacity: 1; }
}

.tech-glow {
  box-shadow: 0 0 20px rgba(69, 183, 209, 0.3);
  border: 1px solid rgba(69, 183, 209, 0.5);
}

.activity-box {
  background: rgba(255, 255, 255, 0.05);
  border-left: 4px solid var(--primary);
  padding: 1rem;
  border-radius: 0 8px 8px 0;
}
</style>

<div class="flex justify-center mb-6">
  <div class="text-8xl">🌊</div>
</div>

# Introduction to LLM and Prompt Engineering
### *How AI will change the way we work and learn*

by **Suki Wang** • *University of Southern California*

<div class="text-lg text-gray-400 mt-3">
"AI is not just about building intelligent machines. It's about understanding intelligence itself - and in doing so, we're forced to confront what makes us uniquely human" - Fei-Fei Li
</div>

<!--
This comprehensive course introduces graduate students to:
- Fundamentals of AI and large language models
- The transformative impact of AI on learning and the workforce
- Core principles and advanced techniques of prompt engineering
- Practical applications across academic and professional domains
- Hands-on experience with real-world AI tools and scenarios
- Capstone projects to demonstrate mastery
- Poll link: https://www.mentimeter.com/app/presentation/alt1qncppj4xpvmottqz9vfefiz39ntp/edit?question=w1mgpz8nnkpk
Course Structure:
- Week 1: AI Foundations & Transformers (3 hours)
- Week 2: Core Prompt Engineering Techniques (3 hours)  
- Week 3: Advanced Applications & Future Implications (3 hours)
-->

---
layout: top-title
color: green-light
align: c
---

:: title ::

# 📊 Let's Get to Know Each Other

:: content ::

<div class="text-center mb-8">
  <div class="text-6xl mb-4">🙋‍♀️🙋‍♂️</div>
  <div class="text-2xl font-semibold text-green-800">Quick Poll: Your LLM Experience</div>
</div>

<div class="grid grid-cols-2 gap-6 mt-8">
  <div class="bg-green-50 p-6 rounded-lg">
    <div class="text-xl font-bold text-green-800 mb-4">📱 Interactive Poll</div>
    <div class="text-green-700 space-y-3">
      <div class="text-base">Scan QR code or visit:</div>
      <div class="bg-white p-3 rounded text-center font-mono text-sm">
        <div class="text-2xl mb-2">📱</div>
        <div><strong>mentimeter.com</strong></div>
        <div>Code: <span class="font-bold text-lg">4927 0705</span></div>
      </div>
      <div class="text-sm italic">Get your phones ready! 📲</div>
    </div>
  </div>
  
  <div class="bg-blue-50 p-6 rounded-lg text-center">
    <div class="text-xl font-bold text-blue-800 mb-4">📱 Scan to Join</div>
    <div class="bg-white p-4 rounded-lg inline-block">
      <img src="/Users/sukiwang/Desktop/AI course/QR.png" alt="Mentimeter QR Code" class="mx-auto max-w-48 rounded">
    </div>
    <div class="text-blue-700 mt-4 text-sm">
      <div class="font-semibold">Or visit: <span class="text-lg">menti.com</span></div>
      <div class="text-xs mt-2 italic">Join the live poll with your phone! 📲</div>
    </div>
  </div>
</div>

<div class="mt-8 text-center text-lg text-green-600 font-semibold">
  🎉 Your responses will help tailor our discussions!
</div>

---
layout: top-title
color: blue-light
align: c
---

:: title ::

# 🤖 What is a Large Language Model?

:: content ::

<div class="text-center mb-8">
  <div class="text-6xl mb-4">🧠 + 📚 + ⚡ = 🤖</div>
  <div class="text-2xl font-semibold text-gray-700">Brain + Knowledge + Computation = LLM</div>
</div>

<div class="grid grid-cols-2 gap-8 mt-8">
  <div class="p-6 bg-blue-50 rounded-lg">
    <div class="text-xl font-bold text-blue-800 mb-4">🎯 Simple Definition</div>
    <div class="text-blue-700 space-y-3">
      <div>• AI system trained on vast amounts of text</div>
      <div>• Learns patterns in human language</div>
      <div>• Can generate human-like responses</div>
      <div>• Understands context and nuance</div>
    </div>
  </div>
  
  <div class="p-6 bg-green-50 rounded-lg">
    <div class="text-xl font-bold text-green-800 mb-4">🏗️ Think of it as...</div>
    <div class="text-green-700 space-y-3">
      <div>• A very sophisticated autocomplete</div>
      <div>• That read most of the internet</div>
      <div>• And learned to think step by step</div>
      <div>• Like a universal text expert</div>
    </div>
  </div>
</div>

<div class="mt-6 text-center text-lg text-gray-600">
  <strong>Key Insight:</strong> LLMs don't just memorize - they learn to reason with language
</div>

---
layout: two-cols-title
columns: is-6
align: c-lt-lt
color: purple-light
---

:: title ::

# 🚀 The Transformer Revolution

:: left ::

<div class="text-center mb-6">
  <div class="text-4xl mb-4">📅</div>
  <div class="text-2xl font-bold">The Timeline</div>
</div>

**🏛️ 2017: "Attention is All You Need"**
- Google researchers publish the Transformer paper
- Revolutionary architecture for processing text

**⚡ 2018-2019: BERT & GPT Era**
- Bidirectional understanding (BERT)
- Generative pre-training (GPT)

**🎯 2020: GPT-3 Breakthrough**
- 175 billion parameters
- First truly capable language model

**🌟 2022-2023: ChatGPT & Beyond**
- Consumer AI revolution begins
- GPT-4, Claude, Gemini emerge

:: right ::

## 🧠 Why Transformers Work

**🔍 Attention Mechanism**
- Focuses on relevant parts of text

**⚡ Parallel Processing** 
- Processes all words simultaneously

**🎯 Context Understanding**
- Sees relationships across entire text

**📈 Scalable Architecture**
- More data + compute = better performance

> **Result:** First AI that truly "understands" language

---
layout: top-title
color: indigo-light
align: c
---

:: title ::

# ⚙️ How Do Transformers Actually Work?

:: content ::

<div class="text-center mb-6">
  <div class="text-2xl font-semibold text-gray-700">Think of it as a sophisticated pattern matching system</div>
</div>

<div class="bg-indigo-50 p-6 rounded-lg mb-6">
  <div class="text-xl font-bold text-indigo-800 mb-4">🔄 The Process (Simplified)</div>
  
```python
Input: "The cat sat on the ___"

1. TOKENIZATION
   "The" → [1043]  "cat" → [2543]  "sat" → [3021]  
   "on" → [319]  "the" → [1043]

2. ATTENTION MECHANISM
   • Which words relate to which?
   • "cat" ← relates to → "sat" (subject-verb)
   • "sat" ← relates to → "on" (verb-preposition) 
   • "on" ← relates to → "the ___" (preposition-object)

3. PATTERN MATCHING
   • Learned: "X sat on the Y" → Y is usually a surface/object
   • Common completions: mat, floor, chair, table...

4. PROBABILITY DISTRIBUTION
   mat: 0.35    floor: 0.28    chair: 0.15    table: 0.12    other: 0.10
```
</div>

<div class="grid grid-cols-3 gap-4 mt-6">
  <div class="text-center">
    <div class="text-3xl mb-2">🎯</div>
    <div class="text-sm font-semibold">Attention</div>
    <div class="text-xs text-gray-600">What to focus on</div>
  </div>
  <div class="text-center">
    <div class="text-3xl mb-2">🧮</div>
    <div class="text-sm font-semibold">Computation</div>
    <div class="text-xs text-gray-600">Process relationships</div>
  </div>
  <div class="text-center">
    <div class="text-3xl mb-2">📊</div>
    <div class="text-sm font-semibold">Prediction</div>
    <div class="text-xs text-gray-600">Generate next word</div>
  </div>
</div>

---
layout: two-cols-title
columns: is-6
align: c-lt-lt
color: green-light
---

:: title ::

# 🏗️ From Training to Your Conversation

:: left ::

<div class="text-center mb-4">
  <div class="text-2xl font-bold">📚 Training Phase</div>
</div>

**1. Data Collection**
- Crawl billions of web pages
- Books, articles, code repositories
- Filter for quality content

**2. Pre-training**
- Learn to predict next word
- "The quick brown fox ___" → "jumps"
- Develops general language understanding

**3. Fine-tuning**
- Human feedback training
- Learn helpful, harmless responses
- Instruction following capabilities

**4. Alignment**
- Constitutional AI methods
- Safety and ethics training
- Reduce harmful outputs

:: right ::

## ⚡ When You Chat with an LLM

**Step 1: You ask a question**
```
"Explain photosynthesis"
```

**Step 2: Model breaks it down**
- Processes each word and context
- Attention mechanism activates 
- Identifies this is a science explanation request

**Step 3: Generates response word by word**
```
"Photosynthesis" → "is" → "the" → "process..."
```

**Step 4: Complete answer appears**
- Coherent, contextual response
- Based on patterns from training data

---
layout: top-title
color: red-light
align: c
---

:: title ::

# 🚫 Why LLM Models Fail at Reasoning

:: content ::

<div class="text-center mb-6">
  <img src="/Users/sukiwang/Desktop/AI course/1756042777605.jpeg" alt="Small LLM reasoning failure example" class="mx-auto max-w-xl rounded-lg shadow-xl border-2 border-gray-300">
</div>

---
layout: top-title
color: red-light
align: c
---

:: title ::

# Pitfall of Small and Weak LLM Models

:: content :: 

<div class="grid grid-cols-2 gap-8 mt-8">
  <div class="bg-blue-50 p-6 rounded-lg">
    <div class="text-xl font-bold text-red-800 mb-3">🧠 Cognitive Limitations</div>
    <div class="text-red-700">
      • Limited parameter count affects reasoning depth<br>
      • Struggles with multi-step logical processes<br>
      • Confuses pattern matching with true reasoning
    </div>
  </div>
  
  <div class="bg-teal-50 p-6 rounded-lg">
    <div class="text-xl font-bold text-orange-800 mb-3">📊 Scale Matters</div>
    <div class="text-orange-700">
      • Emergent abilities appear at larger scales<br>
      • Quality training data becomes crucial<br>
      • Context window limitations impact understanding
    </div>
  </div>
</div>

---
layout: top-title
color: orange-light
align: c
---

:: title ::

# 🎯 Why This Matters for Prompt Engineering

:: content ::

<div class="text-center mb-6">
  <div class="text-2xl font-semibold text-gray-700">Understanding how LLMs work helps you use them better</div>
</div>

<div class="grid grid-cols-2 gap-8">
  <div class="p-6 bg-orange-50 rounded-lg">
    <div class="text-xl font-bold text-orange-800 mb-4">🧠 Mental Model</div>
    <div class="text-orange-700 space-y-3">
      <div><strong>LLMs are prediction machines</strong></div>
      <div>→ Give clear context for better predictions</div>
      <div><strong>They use attention mechanisms</strong></div>
      <div>→ Structure prompts to guide attention</div>
      <div><strong>They think step by step</strong></div>
      <div>→ Ask for reasoning processes</div>
      <div><strong>They learned from examples</strong></div>
      <div>→ Provide examples in your prompts</div>
    </div>
  </div>
  
  <div class="p-6 bg-blue-50 rounded-lg">
    <div class="text-xl font-bold text-blue-800 mb-4">⚡ Practical Implications</div>
    <div class="text-blue-700 space-y-3">
      <div><strong>Specificity matters</strong></div>
      <div>→ "Explain like I'm a grad student" vs "Explain simply"</div>
      <div><strong>Context shapes responses</strong></div>
      <div>→ Set role, tone, format explicitly</div>
      <div><strong>Examples are powerful</strong></div>
      <div>→ Few-shot prompting works</div>
      <div><strong>Iteration improves results</strong></div>
      <div>→ Refine prompts based on outputs</div>
    </div>
  </div>
</div>

<div class="mt-8 p-6 bg-gradient-to-r from-orange-50 to-blue-50 rounded-lg text-center">
  <div class="text-xl font-bold text-gray-800 mb-2">🎓 Ready to Master Prompt Engineering?</div>
  <div class="text-lg text-gray-600">
    Now that you understand the foundation, let's see how the world's leading companies are using this technology...
  </div>
</div>

---
layout: top-title
color: emerald-light
align: c
---

:: title ::

# 🏢 Big Tech is Already Here

:: content ::

<div class="text-center mb-6">
  <div class="text-lg font-semibold text-gray-600">Leading companies are transforming work with AI</div>
</div>

<div class="grid grid-cols-4 gap-6 mt-8">
  <div class="text-center p-4 bg-white rounded-lg shadow-lg">
    <div style="width: 60px; height: 60px; background: #4285F4; border-radius: 12px; margin: 0 auto 12px; display: flex; align-items: center; justify-content: center;">
      <span style="color: white; font-weight: bold; font-size: 24px;">G</span>
    </div>
    <div class="text-sm font-semibold">Google</div>
    <div class="text-xs text-gray-500">Bard + Workspace</div>
  </div>
  
  <div class="text-center p-4 bg-white rounded-lg shadow-lg">
    <div style="width: 60px; height: 60px; background: #00A4EF; border-radius: 12px; margin: 0 auto 12px; display: flex; align-items: center; justify-content: center;">
      <span style="color: white; font-weight: bold; font-size: 20px;">MS</span>
    </div>
    <div class="text-sm font-semibold">Microsoft</div>
    <div class="text-xs text-gray-500">Copilot Ecosystem</div>
  </div>
  
  <div class="text-center p-4 bg-white rounded-lg shadow-lg">
    <div style="width: 60px; height: 60px; background: #412991; border-radius: 12px; margin: 0 auto 12px; display: flex; align-items: center; justify-content: center;">
      <span style="color: white; font-weight: bold; font-size: 20px;">AI</span>
    </div>
    <div class="text-sm font-semibold">OpenAI</div>
    <div class="text-xs text-gray-500">ChatGPT Enterprise</div>
  </div>
  
  <div class="text-center p-4 bg-white rounded-lg shadow-lg">
    <div style="width: 60px; height: 60px; background: #1877F2; border-radius: 12px; margin: 0 auto 12px; display: flex; align-items: center; justify-content: center;">
      <span style="color: white; font-weight: bold; font-size: 20px;">M</span>
    </div>
    <div class="text-sm font-semibold">Meta</div>
    <div class="text-xs text-gray-500">Llama + AI Agents</div>
  </div>
</div>

<div class="text-center mt-6 text-lg font-semibold text-gray-700">
  💡 These aren't future plans - they're deployed at scale today
</div>

---
layout: two-cols-title
columns: is-6
align: c-lt-lt
color: blue-light
---

:: title ::

# 🚀 Google's AI Revolution

:: left ::

<div class="mb-6">
  <div style="width: 80px; height: 80px; background: #4285F4; border-radius: 16px; margin: 0 auto 16px; display: flex; align-items: center; justify-content: center;">
    <span style="color: white; font-weight: bold; font-size: 32px;">G</span>
  </div>
</div>

**Real Impact:**
- 🔍 **Search**: 15% of daily queries are AI-generated
- 📧 **Gmail**: 60% productivity boost in email composition
- 📊 **Workspace**: Smart suggestions in Docs, Sheets
- 💻 **Code**: 55% faster development with AI assistance

:: right ::

<div class="bg-blue-50 p-6 rounded-lg">
  <div class="text-xl font-bold text-blue-800 mb-4">📈 LLMOps at Scale</div>
  
  ```
  Prompt Engineering Pipeline:
  
  1. Intent Detection
     └── Multi-model routing
  
  2. Context Injection  
     └── Dynamic RAG systems
     
  3. Response Generation
     └── Safety + Quality filters
     
  4. Continuous Learning
     └── User feedback loops
  ```
  
  <div class="text-sm text-blue-600 mt-4">
    <strong>Key Insight:</strong> Google processes 8.5 billion searches daily with AI-enhanced prompting
  </div>
</div>

---
layout: two-cols-title
columns: is-6
align: c-lt-lt
color: indigo-light
---

:: title ::

# 💼 Microsoft's Copilot Empire

:: left ::

<div class="mb-6">
  <div style="width: 80px; height: 80px; background: #00A4EF; border-radius: 16px; margin: 0 auto 16px; display: flex; align-items: center; justify-content: center;">
    <span style="color: white; font-weight: bold; font-size: 28px;">MS</span>
  </div>
</div>

**Enterprise Transformation:**
- 💻 **GitHub Copilot**: 55% faster coding
- 📝 **M365 Copilot**: 70% time saved on documents
- 🔐 **Security Copilot**: 40% faster threat analysis
- ⚡ **Power Platform**: Citizen developers create apps with prompts

:: right ::

<div class="bg-indigo-50 p-6 rounded-lg">
  <div class="text-xl font-bold text-indigo-800 mb-4">🏗️ Prompt Architecture</div>
  
  ```
  Microsoft's Approach:
  
  System → Context → Examples → Task
     ↓        ↓        ↓       ↓
  "You are   User     Few     "Generate
   a coding  session  shot    the sales
   expert"   data     demos   report"
  
  Safety Layer: Content filtering
  Performance: Sub-200ms response
  Scale: 100M+ users daily
  ```
  
  <div class="text-sm text-indigo-600 mt-4">
    <strong>Business Impact:</strong> $10B+ revenue from AI products in 2024
  </div>
</div>

---
layout: two-cols-title
columns: is-6
align: c-lt-lt
color: purple-light
---

:: title ::

# 🧠 OpenAI's Enterprise Revolution

:: left ::

<div class="mb-6">
  <div style="width: 80px; height: 80px; background: #412991; border-radius: 16px; margin: 0 auto 16px; display: flex; align-items: center; justify-content: center;">
    <span style="color: white; font-weight: bold; font-size: 24px;">AI</span>
  </div>
</div>

**ChatGPT Enterprise Impact:**
- 🏢 **Fortune 500**: 80% are customers
- 📈 **Productivity**: 4x faster analysis tasks  
- 🎯 **Custom GPTs**: 100,000+ specialized models
- 🔒 **Security**: Enterprise-grade deployment

:: right ::

<div class="bg-purple-50 p-6 rounded-lg">
  <div class="text-xl font-bold text-purple-800 mb-4">⚙️ Prompt Engineering Best Practices</div>
  
  ```
  OpenAI's Framework:
  
  1. Clear Instructions
     "Act as a [role] to [task]"
  
  2. Provide Context  
     Include relevant background
     
  3. Use Examples
     Show desired output format
     
  4. Iterative Refinement
     Test → Analyze → Improve
  ```
  
  <div class="text-sm text-purple-600 mt-4">
    <strong>Success Metric:</strong> 92% of users report significant productivity gains
  </div>
</div>

---
layout: two-cols-title
columns: is-6
align: c-lt-lt
color: green-light
---

:: title ::

# 🦙 Meta's Open Source Strategy

:: left ::

<div class="mb-6">
  <div style="width: 80px; height: 80px; background: #1877F2; border-radius: 16px; margin: 0 auto 16px; display: flex; align-items: center; justify-content: center;">
    <span style="color: white; font-weight: bold; font-size: 28px;">M</span>
  </div>
</div>

**Llama Impact:**
- 🚀 **Open Source**: 200M+ downloads of Llama models
- 💬 **WhatsApp**: AI assistants for 2B+ users
- 🎯 **Instagram**: Content generation & moderation
- 🔬 **Research**: Advancing multimodal AI capabilities

:: right ::

<div class="bg-green-50 p-6 rounded-lg">
  <div class="text-xl font-bold text-green-800 mb-4">🧠 Prompt Strategy</div>
  
  ```
  Meta's Multi-Agent Framework:
  
  Content Creation:
  "Generate post variations for
   different audiences:
   - Gen Z: casual, emoji-heavy
   - Professional: formal tone
   - Brand voice: [company style]"
   
  Safety Filtering:
  System prompts filter harmful content
  before user interaction
  ```
  
  <div class="text-sm text-green-600 mt-4">
    <strong>Scale Impact:</strong> Processing 100B+ messages daily with AI assistance
  </div>
</div>

---
layout: two-cols-title
columns: is-6
align: c-lt-lt
color: orange-light
---

:: title ::

# 📦 Amazon's AI Infrastructure

:: left ::

<div class="mb-6">
  <div style="width: 80px; height: 80px; background: #FF9900; border-radius: 16px; margin: 0 auto 16px; display: flex; align-items: center; justify-content: center;">
    <span style="color: white; font-weight: bold; font-size: 28px;">A</span>
  </div>
</div>

**AWS + Retail Innovation:**
- 🛒 **Alexa**: 100M+ devices using conversational AI
- 📦 **Logistics**: AI-optimized warehouse operations
- ☁️ **AWS Bedrock**: Enterprise LLM platform
- 🛍️ **Recommendations**: Personalized shopping at scale

:: right ::

<div class="bg-orange-50 p-6 rounded-lg">
  <div class="text-xl font-bold text-orange-800 mb-4">⚙️ Enterprise Prompting</div>
  
  ```
  Amazon's Approach:
  
  Customer Service:
  "Analyze customer complaint:
   [complaint text]
   
   Provide:
   1. Sentiment classification
   2. Issue category
   3. Recommended resolution
   4. Escalation priority"
   
  Multi-step reasoning with validation
  ```
  
  <div class="text-sm text-orange-600 mt-4">
    <strong>Business Result:</strong> 40% reduction in customer service resolution time
  </div>
</div>

---
layout: two-cols-title
columns: is-6
align: c-lt-lt
color: cyan-light
---

:: title ::

# 🤖 Anthropic's Safety-First AI

:: left ::

<div class="mb-6">
  <div style="width: 80px; height: 80px; background: #D97706; border-radius: 16px; margin: 0 auto 16px; display: flex; align-items: center; justify-content: center;">
    <span style="color: white; font-weight: bold; font-size: 20px;">Aₙ</span>
  </div>
</div>

**Constitutional AI Leadership:**
- 🛡️ **Claude**: Enterprise-grade safety & reasoning
- 🔬 **Research**: Constitutional AI methodology
- 🏢 **Enterprise**: High-stakes decision support
- 📚 **Education**: Advanced reasoning for complex tasks

:: right ::

<div class="bg-cyan-50 p-6 rounded-lg">
  <div class="text-xl font-bold text-cyan-800 mb-4">🎯 Constitutional Prompting</div>
  
  ```
  Anthropic's Method:
  
  1. Initial Prompt:
     "Analyze this legal document..."
     
  2. Constitutional Check:
     "Is this response helpful, 
      harmless, and honest?"
      
  3. Self-Correction:
     "Revise to be more accurate..."
     
  Multi-layer safety validation
  ```
  
  <div class="text-sm text-cyan-600 mt-4">
    <strong>Reliability:</strong> 95%+ accuracy on complex reasoning tasks
  </div>
</div>

---
layout: top-title
color: sky-light
align: c
---

:: title ::

# 🌊 The AI Tsunami is Here

:: content ::

<div class="text-center mb-8">
  <div class="text-4xl mb-4">⚠️ 💼 📈 🎓</div>
  <div class="text-2xl font-bold text-gray-700">Your field will change fundamentally in the next 2-3 years</div>
</div>

<div class="grid grid-cols-2 gap-8 mt-6">
  <div class="p-6 bg-red-50 rounded-lg border-l-4 border-red-400">
    <div class="text-xl font-bold text-red-700 mb-3">⚠️ The Reality</div>
    <div class="text-red-600 space-y-2">
      <div>• AI tools are already transforming research</div>
      <div>• Traditional coding workflows becoming obsolete</div>
      <div>• Data analysis is being automated</div>
      <div>• Writing and documentation changing rapidly</div>
    </div>
  </div>
  
  <div class="p-6 bg-blue-50 rounded-lg border-l-4 border-blue-400">
    <div class="text-xl font-bold text-blue-700 mb-3">💪 The Solution</div>
    <div class="text-blue-600 space-y-2">
      <div>• Master human-AI collaboration</div>
      <div>• Learn to direct AI effectively</div>
      <div>• Become an AI-powered researcher</div>
      <div>• Stay ahead of the curve</div>
    </div>
  </div>
</div>

<div class="mt-8 p-6 bg-gradient-to-r from-purple-50 to-pink-50 rounded-lg text-center">
  <div class="text-xl font-bold text-purple-700 mb-2">🎯 This Course Will Teach You</div>
  <div class="text-lg text-purple-600">
    How to become the person who leverages AI instead of being replaced by it
  </div>
</div>

---
layout: center
class: text-center
---

# 🏗️ How Work Actually Gets Done Today vs Tomorrow

<div class="text-6xl mb-6">📊</div>

<div class="grid grid-cols-2 gap-8 mt-8">
  <div class="p-6 bg-gray-50 rounded-lg">
    <div class="text-2xl mb-4 font-semibold text-gray-700">📚 Traditional Workflow</div>
    <div class="space-y-3 text-gray-600">
      <div class="flex items-start">
        <div class="text-lg mr-2">🔍</div>
        <div>Manual literature reviews taking weeks</div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">💻</div>
        <div>Writing code from scratch, debugging line by line</div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">📊</div>
        <div>Manual data cleaning and analysis</div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">✍️</div>
        <div>Writing papers paragraph by paragraph</div>
      </div>
    </div>
  </div>
  
  <div class="p-6 bg-green-50 rounded-lg">
    <div class="text-2xl mb-4 font-semibold text-green-700">🤖 AI-Enhanced Workflow</div>
    <div class="space-y-3 text-green-600">
      <div class="flex items-start">
        <div class="text-lg mr-2">⚡</div>
        <div>AI synthesizes 100+ papers in minutes</div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">🎯</div>
        <div>AI generates, reviews, and optimizes code</div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">📈</div>
        <div>AI finds patterns and suggests analyses</div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">📝</div>
        <div>AI drafts, refines, and structures content</div>
      </div>
    </div>
  </div>
</div>

<div class="mt-8 p-6 bg-yellow-50 rounded-lg text-center">
  <div class="text-xl font-bold text-yellow-700 mb-2">🔑 The Key Skill</div>
  <div class="text-lg text-yellow-600">
    The ability to effectively communicate with and direct AI systems
  </div>
</div>

---
layout: top-title
color: emerald-light
align: c
---

:: title ::

# 📢 Why Prompt Engineering Matters for YOUR Future

:: content ::

<div class="text-center mb-8">
  <div class="text-4xl mb-4">💼 → 🤖 → 🎆</div>
  <div class="text-2xl font-semibold text-gray-700">Career Success = AI Collaboration Skills</div>
</div>

<div class="grid grid-cols-3 gap-6 mt-6">
  <div class="text-center p-6 bg-red-50 rounded-lg">
    <div class="text-3xl mb-3">❌</div>
    <div class="text-lg font-semibold text-red-600">Without AI Skills</div>
    <div class="text-sm text-red-500 space-y-1">
      <div>Spend weeks on literature reviews</div>
      <div>Struggle with coding problems</div>
      <div>Limited analytical capabilities</div>
      <div>Slower research progress</div>
    </div>
  </div>
  
  <div class="text-center p-6 bg-yellow-50 rounded-lg">
    <div class="text-3xl mb-3">⚠️</div>
    <div class="text-lg font-semibold text-yellow-600">Basic AI Use</div>
    <div class="text-sm text-yellow-500 space-y-1">
      <div>Get simple answers</div>
      <div>Basic text generation</div>
      <div>Inconsistent results</div>
      <div>Limited effectiveness</div>
    </div>
  </div>
  
  <div class="text-center p-6 bg-green-50 rounded-lg">
    <div class="text-3xl mb-3">✅</div>
    <div class="text-lg font-semibold text-green-600">Prompt Engineering Mastery</div>
    <div class="text-sm text-green-500 space-y-1">
      <div>Complex problem decomposition</div>
      <div>Sophisticated analysis workflows</div>
      <div>Consistent, high-quality outputs</div>
      <div>10x productivity gains</div>
    </div>
  </div>
</div>

<div class="mt-8 p-6 bg-blue-50 rounded-lg text-center">
  <div class="text-xl font-bold text-blue-700 mb-2">💡 The Bottom Line</div>
  <div class="text-lg text-blue-600">
    Prompt engineering is the new "digital literacy" - essential for any knowledge worker
  </div>
</div>

<!--
Key concepts to cover:
- Transformer architecture: encoder-decoder, self-attention, positional encoding
- How LLMs learn patterns from text
- Scale effects: why bigger models perform better
- Emergent capabilities that arise from scale
- Training process: pre-training on massive datasets
- Fine-tuning for specific tasks
- The attention mechanism and why it's revolutionary
- Parallel processing advantages over RNNs

Interactive element: Show attention visualization, demonstrate how the model "pays attention" to different parts of input when generating responses
-->

---
layout: top-title
color: emerald-light
align: c
---

:: title ::

# 🤖 What Are Large Language Models?

:: content ::

<div class="text-center">
  <div class="brain-animation mb-8 flex items-center justify-center">
    <div class="text-4xl">🧠 → 🔄 → 💬 → ✨</div>
  </div>
  
  <div class="text-2xl mb-6">
    <span class="gradient-text">The Technology Behind AI Revolution</span>
  </div>
</div>

<div class="grid grid-cols-3 gap-6 mt-6">
  <div class="text-center p-4 tech-glow rounded-lg">
    <div class="text-3xl mb-2">📚</div>
    <div class="text-lg font-semibold">Trained on Text</div>
    <div class="text-sm text-gray-600">Learned from billions of documents</div>
  </div>
  
  <div class="text-center p-4 tech-glow rounded-lg">
    <div class="text-3xl mb-2">🧠</div>
    <div class="text-lg font-semibold">Pattern Recognition</div>
    <div class="text-sm text-gray-600">Understands language structures</div>
  </div>
  
  <div class="text-center p-4 tech-glow rounded-lg">
    <div class="text-3xl mb-2">🗣️</div>
    <div class="text-lg font-semibold">Human-like Responses</div>
    <div class="text-sm text-gray-600">Generates contextual answers</div>
  </div>
</div>

<div class="mt-8 p-6 bg-blue-50 rounded-lg text-center">
  <div class="text-xl font-bold text-blue-700 mb-2">💡 Key Insight</div>
  <div class="text-lg text-blue-600">
    LLMs don't "know" facts - they predict the most likely next word based on patterns
  </div>
</div>

---
layout: top-title
color: purple-light
align: c
---

:: title ::

# 🏗️ Transformer Architecture: The Engine Behind AI

:: content ::

<div class="text-center mb-6">
  <div class="text-2xl font-semibold mb-4">From Text Input to Prediction</div>
</div>

```
INPUT TEXT: "The future of AI is"
     ↓
┌─────────────────────────────────────────────────────────┐
│  TOKENIZATION: ["The", "future", "of", "AI", "is"]     │
│  TOKEN IDs: [464, 2003, 286, 14371, 318]              │
└─────────────────────────────────────────────────────────┘
     ↓
┌─────────────────────────────────────────────────────────┐
│  EMBEDDING LAYER                                        │
│  Each token → 768-dimensional vector                   │
│  + Positional encoding (where in sequence)            │
└─────────────────────────────────────────────────────────┘
     ↓
┌─────────────────────────────────────────────────────────┐
│  TRANSFORMER BLOCKS (12 layers)                        │
│  ┌───────────────────────────────────────────────────┐ │
│  │  Multi-Head Attention (12 heads)                 │ │
│  │  - Query, Key, Value matrices                    │ │
│  │  - Self-attention: tokens "talk" to each other   │ │
│  └───────────────────────────────────────────────────┘ │
│  ┌───────────────────────────────────────────────────┐ │
│  │  Feed Forward Network                             │ │
│  │  768 → 3072 → 768 dimensions                    │ │
│  └───────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────┘
     ↓
┌─────────────────────────────────────────────────────────┐
│  OUTPUT LAYER                                           │
│  Final 768-dim vector → 50,257 probabilities          │
│  Each probability = likelihood of next word            │
└─────────────────────────────────────────────────────────┘
     ↓
OUTPUT: "promising" (highest probability: 0.23)
```

<div class="mt-6 text-center text-gray-600">
  Each layer refines understanding, building from syntax to meaning to context
</div>

---
layout: top-title
color: indigo-light
align: c
---

:: title ::

# 🎯 Attention Mechanism: How AI "Focuses"

:: content ::

<div class="text-center mb-6">
  <div class="text-2xl font-semibold mb-2">Self-Attention in Action</div>
  <div class="text-lg text-gray-600">Example: "The cat sat on the mat"</div>
</div>

<div class="grid grid-cols-2 gap-8">
  <div class="bg-blue-50 p-6 rounded-lg">
    <div class="text-xl font-bold text-blue-700 mb-4">🔍 Step 1: Create Q, K, V</div>
    ```
    For each word, create:
    
    Query (Q):  "What am I looking for?"
    Key (K):    "What do I represent?"
    Value (V):  "What information do I carry?"
    
    Example for "cat":
    Q_cat = [0.2, 0.8, 0.1, ...] (768 dimensions)
    K_cat = [0.5, 0.3, 0.9, ...]
    V_cat = [0.7, 0.4, 0.6, ...]
    ```
  </div>
  
  <div class="bg-green-50 p-6 rounded-lg">
    <div class="text-xl font-bold text-green-700 mb-4">⚡ Step 2: Calculate Attention</div>
    ```
    Attention Score = Q · K^T
    
    How much should "cat" pay attention to:
    - "The":  0.1  (low - just an article)
    - "cat":  0.9  (high - self-reference)
    - "sat":  0.7  (high - related action)
    - "on":   0.2  (medium - relationship)
    - "mat":  0.4  (medium - object of action)
    
    After softmax: [0.05, 0.45, 0.35, 0.10, 0.15]
    ```
  </div>
</div>

<div class="mt-6 p-6 bg-yellow-50 rounded-lg">
  <div class="text-xl font-bold text-yellow-700 mb-3">🎭 Step 3: Weighted Combination</div>
  <div class="text-center">
    ```
    Final representation of "cat" = 
    0.05×V_The + 0.45×V_cat + 0.35×V_sat + 0.10×V_on + 0.15×V_mat
    
    Result: Rich representation that includes context from all related words
    ```
  </div>
</div>

---
layout: top-title
color: emerald-light
align: c
---

:: title ::

# 🔄 How LLMs Generate Text: The Thinking Process

:: content ::

<div class="text-center mb-6">
  <div class="text-2xl font-semibold mb-2">From Prompt to Response</div>
  <div class="text-lg text-gray-600">Step-by-step text generation</div>
</div>

```
PROMPT: "Explain quantum computing in simple terms"

┌─────────────────────────────────────────────────────────────────┐
│ STEP 1: Process Input                                           │
│ • Tokenize prompt                                               │
│ • Convert to embeddings                                         │
│ • Run through all transformer layers                           │
│ Result: Rich representation of input meaning                    │
└─────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────┐
│ STEP 2: Predict Next Token                                     │
│ Top predictions:                                                │
│ • "Quantum"    : 0.31 ← Highest probability                   │
│ • "Imagine"    : 0.18                                          │
│ • "Think"      : 0.15                                          │
│ • "Unlike"     : 0.12                                          │
│ Selection: "Quantum" (using temperature sampling)              │
└─────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────┐
│ STEP 3: Update Context                                         │
│ New input: "Explain quantum computing in simple terms Quantum" │
│ Re-process entire sequence through transformer                  │
│ Attention now includes relationship to "Quantum"               │
└─────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────┐
│ STEP 4: Predict Next Token                                     │
│ Top predictions:                                                │
│ • "computing"  : 0.45 ← Clear winner                          │
│ • "mechanics"  : 0.23                                          │
│ • "physics"    : 0.18                                          │
│ Continue until stopping condition...                           │
└─────────────────────────────────────────────────────────────────┘
```

<div class="mt-6 p-6 bg-purple-50 rounded-lg text-center">
  <div class="text-xl font-bold text-purple-700 mb-2">🧠 Key Insight</div>
  <div class="text-lg text-purple-600">
    Each word is predicted based on ALL previous words + learned patterns from training
  </div>
</div>

---
layout: top-title-two-cols
align: c-lt-lt
columns: is-6
color: amber-light
---

:: title ::

# ⚙️ Training vs Inference: Two Different Modes

:: left ::

## 🏋️ Training Phase
```
MASSIVE DATASET
"The cat sat on the mat"
        ↓
Predict: "cat" → Model guesses: "dog" ❌
         Calculate error
         Adjust 175B parameters
         
"sat" → Model guesses: "ran" ❌
        Calculate error  
        Adjust parameters
        
Repeat trillions of times
Result: Pattern recognition
```

**Objective:** Learn language patterns
**Time:** Months of computation
**Cost:** Millions of dollars
**Data:** Trillions of words

:: right ::

## 🚀 Inference Phase
```
USER PROMPT
"Write a poem about AI"
        ↓
Use learned patterns
No parameter updates
        
Generate: "In circuits bright..."
Predict each word using
existing knowledge
        
Speed: Milliseconds per word
Cost: Pennies per request
```

**Objective:** Generate helpful text
**Time:** Seconds
**Cost:** Very low
**Data:** Just your prompt

<div class="mt-6 p-4 bg-orange-50 rounded-lg">
  <div class="text-center font-bold text-orange-700">
    🎯 You interact with the inference phase - the "thinking" is already baked in!
  </div>
</div>

---
layout: top-title
color: red-light
align: c
---

:: title ::

# 🎭 Understanding AI "Intelligence" vs Human Intelligence

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div class="p-6 bg-blue-50 rounded-lg">
    <div class="text-2xl font-bold text-blue-700 mb-4">🤖 How AI "Thinks"</div>
    <div class="space-y-3 text-blue-600">
      <div class="flex items-start">
        <div class="text-lg mr-2">📊</div>
        <div>
          <div class="font-semibold">Statistical Pattern Matching</div>
          <div class="text-sm">"This combination of words typically leads to..."</div>
        </div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">🔢</div>
        <div>
          <div class="font-semibold">Probability Calculations</div>
          <div class="text-sm">175 billion parameters working simultaneously</div>
        </div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">📚</div>
        <div>
          <div class="font-semibold">Training Data Synthesis</div>
          <div class="text-sm">Combines patterns from millions of examples</div>
        </div>
      </div>
    </div>
  </div>
  
  <div class="p-6 bg-green-50 rounded-lg">
    <div class="text-2xl font-bold text-green-700 mb-4">🧠 How Humans Think</div>
    <div class="space-y-3 text-green-600">
      <div class="flex items-start">
        <div class="text-lg mr-2">💭</div>
        <div>
          <div class="font-semibold">Conceptual Understanding</div>
          <div class="text-sm">True comprehension of meaning and context</div>
        </div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">🎯</div>
        <div>
          <div class="font-semibold">Intentional Goals</div>
          <div class="text-sm">Conscious purpose and planning</div>
        </div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">🌟</div>
        <div>
          <div class="font-semibold">Creative Intuition</div>
          <div class="text-sm">Novel insights and breakthrough thinking</div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="mt-8 p-6 bg-purple-50 rounded-lg">
  <div class="text-center">
    <div class="text-2xl font-bold text-purple-700 mb-4">🤝 The Power of Collaboration</div>
    <div class="grid grid-cols-3 gap-4 text-purple-600">
      <div class="text-center">
        <div class="text-3xl mb-2">⚡</div>
        <div class="font-semibold">AI Strengths</div>
        <div class="text-sm">Pattern recognition, speed, consistency, memory</div>
      </div>
      <div class="text-center">
        <div class="text-3xl mb-2">➕</div>
        <div class="font-semibold">Combined</div>
        <div class="text-sm">Amplified capabilities for both</div>
      </div>
      <div class="text-center">
        <div class="text-3xl mb-2">🎯</div>
        <div class="font-semibold">Human Strengths</div>
        <div class="text-sm">Creativity, judgment, ethics, strategic thinking</div>
      </div>
    </div>
  </div>
</div>

---
layout: top-title-two-cols
align: c-lt-lt
columns: is-6
color: sky-light
---

:: title ::

# 📊 Real Examples: Traditional vs AI-Enhanced Research

:: left ::

## 📚 Traditional Research Process
<div class="space-y-4">
  <div class="p-4 bg-gray-50 rounded">
    <div class="font-bold">Literature Review (3-4 weeks)</div>
    <div class="text-sm">Manually search databases, read papers, take notes, synthesize findings</div>
  </div>
  <div class="p-4 bg-gray-50 rounded">
    <div class="font-bold">Data Analysis (2-3 weeks)</div>
    <div class="text-sm">Learn statistical methods, write code, debug errors, interpret results</div>
  </div>
  <div class="p-4 bg-gray-50 rounded">
    <div class="font-bold">Writing (2-4 weeks)</div>
    <div class="text-sm">Draft sections, revise multiple times, format references manually</div>
  </div>
</div>

:: right ::

## 🤖 AI-Enhanced Research Process
<div class="space-y-4">
  <div class="p-4 bg-green-50 rounded">
    <div class="font-bold">Literature Review (2-3 days)</div>
    <div class="text-sm">AI synthesizes 100+ papers, identifies gaps, generates summaries with proper prompting</div>
  </div>
  <div class="p-4 bg-green-50 rounded">
    <div class="font-bold">Data Analysis (3-5 days)</div>
    <div class="text-sm">AI suggests methods, generates code, explains results, creates visualizations</div>
  </div>
  <div class="p-4 bg-green-50 rounded">
    <div class="font-bold">Writing (3-5 days)</div>
    <div class="text-sm">AI drafts sections, improves clarity, formats references, suggests improvements</div>
  </div>
</div>

<!--
Discuss the paradigm shift:
- From information scarcity to information abundance
- From memorization to critical thinking and synthesis
- The role of AI as a tutor, collaborator, and thinking partner
- How AI changes research methodologies for graduate students
- The importance of developing AI literacy
- Ethical considerations in AI-assisted learning

Activity: Have students reflect on their current learning methods and identify areas where AI could enhance their academic work
-->

---
layout: top-title
color: amber-light
align: c
---

:: title ::

# 🎯 Course Structure: From Zero to Prompt Engineering Expert

:: content ::

<div class="grid grid-cols-3 gap-6 mt-8">
  <div class="text-center p-6 bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl">
    <div class="text-4xl mb-3">🏗️</div>
    <div class="text-xl mb-2 font-bold">Week 1</div>
    <div class="text-lg mb-2 text-blue-600">Foundation & Basics</div>
    <div class="text-sm text-gray-600">AI fundamentals, simple prompts, first hands-on exercises</div>
  </div>
  
  <div class="text-center p-6 bg-gradient-to-br from-green-50 to-teal-50 rounded-xl">
    <div class="text-4xl mb-3">⚙️</div>
    <div class="text-xl mb-2 font-bold">Week 2</div>
    <div class="text-lg mb-2 text-green-600">Core Techniques</div>
    <div class="text-sm text-gray-600">Advanced prompting methods, systematic approaches</div>
  </div>
  
  <div class="text-center p-6 bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl">
    <div class="text-4xl mb-3">🚀</div>
    <div class="text-xl mb-2 font-bold">Week 3</div>
    <div class="text-lg mb-2 text-purple-600">Mastery & Applications</div>
    <div class="text-sm text-gray-600">Complex workflows, ethics, real-world projects</div>
  </div>
</div>

<div class="mt-8 p-6 bg-gradient-to-r from-orange-50 to-red-50 rounded-lg">
  <div class="text-center">
    <div class="text-2xl font-bold text-orange-700 mb-4">🎆 By The End Of This Course</div>
    <div class="grid grid-cols-2 gap-6 text-left">
      <div class="space-y-2">
        <div class="flex items-center"><div class="text-lg mr-2">✅</div><div>Design complex multi-step prompting workflows</div></div>
        <div class="flex items-center"><div class="text-lg mr-2">✅</div><div>Automate your research and analysis processes</div></div>
        <div class="flex items-center"><div class="text-lg mr-2">✅</div><div>Create AI-powered tools for your field</div></div>
      </div>
      <div class="space-y-2">
        <div class="flex items-center"><div class="text-lg mr-2">✅</div><div>Understand ethical AI use in academia</div></div>
        <div class="flex items-center"><div class="text-lg mr-2">✅</div><div>Build a portfolio of AI-enhanced projects</div></div>
        <div class="flex items-center"><div class="text-lg mr-2">✅</div><div>Position yourself as an AI-savvy expert</div></div>
      </div>
    </div>
  </div>
</div>

---
layout: top-title
align: c
---

:: title ::

# 🛠️ Week 1 Activities & Assignments

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div class="activity-box">
    <div class="text-xl font-bold text-blue-600 mb-3">🎯 In-Class Activity</div>
    <div class="text-lg font-semibold mb-2">AI Conversation Experiment</div>
    <div class="text-sm text-gray-700">
      • Work in pairs with ChatGPT/Claude<br>
      • Ask the same question using different approaches<br>
      • Compare response quality and style<br>
      • Identify what makes prompts effective<br>
      • Share findings with class
    </div>
  </div>
  
  <div class="activity-box">
    <div class="text-xl font-bold text-green-600 mb-3">📋 Assignment</div>
    <div class="text-lg font-semibold mb-2">Personal AI Impact Assessment</div>
    <div class="text-sm text-gray-700">
      • Analyze your current field of study<br>
      • Identify 3 ways AI could enhance your work<br>
      • Research 2 AI tools relevant to your field<br>
      • Write 500-word reflection on implications<br>
      • Due: Before Week 2
    </div>
  </div>
</div>

<div class="mt-8 p-6 bg-purple-50 rounded-lg">
  <div class="text-xl font-bold text-purple-700 mb-3">🎯 Capstone Project - Phase 1</div>
  <div class="text-lg font-semibold mb-2">Choose Your Domain</div>
  <div class="text-gray-700">
    Select a specific problem in your field of study that could benefit from AI assistance. This will be the foundation for your 3-week capstone project. Submit a 1-paragraph proposal.
  </div>
</div>

---
layout: center
class: text-center
---

# Week 2: Core Prompt Engineering
## *The Art and Science of Communication*

<div class="text-6xl mb-6">⚡</div>

<div class="grid grid-cols-2 gap-8 mt-8">
  <div class="text-left">
    <div class="text-2xl mb-4 font-semibold text-teal-500">🎓 Learning Objectives</div>
    <div class="space-y-2 text-lg">
      <div>• Master core prompting techniques</div>
      <div>• Understand prompt anatomy</div>
      <div>• Apply systematic approaches</div>
      <div>• Handle common pitfalls</div>
    </div>
  </div>
  
  <div class="text-left">
    <div class="text-2xl mb-4 font-semibold text-blue-500">⏰ Schedule (3 hours)</div>
    <div class="space-y-2 text-lg">
      <div>• 45min: Prompt anatomy & structure</div>
      <div>• 45min: Core techniques & patterns</div>
      <div>• 45min: Advanced prompting methods</div>
      <div>• 45min: Hands-on practice session</div>
    </div>
  </div>
</div>

---
layout: top-title
color: indigo-light
align: c
---

:: title ::

# 🧩 Anatomy of an Effective Prompt

:: content ::

<div class="text-center mb-8">
  <div class="text-4xl mb-4">🎯 → 📝 → 🔧 → ✨</div>
  <div class="text-xl text-gray-600">Goal → Context → Instructions → Output</div>
</div>

<div class="grid grid-cols-4 gap-4 mt-6">
  <div class="text-center p-4 bg-blue-50 rounded-lg">
    <div class="text-3xl mb-2">🎯</div>
    <div class="text-lg font-semibold">Role & Goal</div>
    <div class="text-sm text-gray-600">Define the AI's perspective and objective</div>
  </div>
  
  <div class="text-center p-4 bg-green-50 rounded-lg">
    <div class="text-3xl mb-2">📝</div>
    <div class="text-lg font-semibold">Context</div>
    <div class="text-sm text-gray-600">Provide relevant background information</div>
  </div>
  
  <div class="text-center p-4 bg-yellow-50 rounded-lg">
    <div class="text-3xl mb-2">🔧</div>
    <div class="text-lg font-semibold">Instructions</div>
    <div class="text-sm text-gray-600">Specify desired actions and constraints</div>
  </div>
  
  <div class="text-center p-4 bg-purple-50 rounded-lg">
    <div class="text-3xl mb-2">✨</div>
    <div class="text-lg font-semibold">Output Format</div>
    <div class="text-sm text-gray-600">Define structure and style requirements</div>
  </div>
</div>

<!--
Key components to cover in detail:
1. Role Definition:
   - "You are a..." statements
   - Expertise specification
   - Perspective setting

2. Context Setting:
   - Background information
   - Constraints and limitations  
   - Relevant examples

3. Task Instructions:
   - Clear, specific directives
   - Step-by-step breakdowns
   - Success criteria

4. Output Specification:
   - Format requirements (JSON, markdown, etc.)
   - Length constraints
   - Style preferences
   - Examples of desired output

Show before/after examples of prompts with and without proper structure
-->

---
layout: top-title
align: c
---

:: title ::

# 🎨 Core Prompting Techniques

:: content ::

<div class="grid grid-cols-3 gap-6 mt-6">
  <div class="p-5 bg-gradient-to-br from-red-50 to-pink-50 rounded-lg">
    <div class="text-3xl mb-3">🔗</div>
    <div class="text-lg font-bold text-red-600 mb-2">Chain of Thought</div>
    <div class="text-sm text-gray-700">
      Guide the AI through step-by-step reasoning
    </div>
    <div class="text-xs text-gray-500 mt-2 font-mono bg-white p-2 rounded">
      "Let's think through this step by step..."
    </div>
  </div>
  
  <div class="p-5 bg-gradient-to-br from-blue-50 to-indigo-50 rounded-lg">
    <div class="text-3xl mb-3">🎭</div>
    <div class="text-lg font-bold text-blue-600 mb-2">Role Playing</div>
    <div class="text-sm text-gray-700">
      Assign specific expertise and perspective
    </div>
    <div class="text-xs text-gray-500 mt-2 font-mono bg-white p-2 rounded">
      "As a senior researcher in..."
    </div>
  </div>
  
  <div class="p-5 bg-gradient-to-br from-green-50 to-emerald-50 rounded-lg">
    <div class="text-3xl mb-3">📋</div>
    <div class="text-lg font-bold text-green-600 mb-2">Few-Shot Learning</div>
    <div class="text-sm text-gray-700">
      Provide examples to guide output style
    </div>
    <div class="text-xs text-gray-500 mt-2 font-mono bg-white p-2 rounded">
      "Here are 3 examples..."
    </div>
  </div>
  
  <div class="p-5 bg-gradient-to-br from-purple-50 to-violet-50 rounded-lg">
    <div class="text-3xl mb-3">🏗️</div>
    <div class="text-lg font-bold text-purple-600 mb-2">Scaffolding</div>
    <div class="text-sm text-gray-700">
      Break complex tasks into manageable parts
    </div>
    <div class="text-xs text-gray-500 mt-2 font-mono bg-white p-2 rounded">
      "First... then... finally..."
    </div>
  </div>
  
  <div class="p-5 bg-gradient-to-br from-orange-50 to-amber-50 rounded-lg">
    <div class="text-3xl mb-3">🎯</div>
    <div class="text-lg font-bold text-orange-600 mb-2">Constraint Setting</div>
    <div class="text-sm text-gray-700">
      Define boundaries and limitations
    </div>
    <div class="text-xs text-gray-500 mt-2 font-mono bg-white p-2 rounded">
      "In exactly 200 words..."
    </div>
  </div>
  
  <div class="p-5 bg-gradient-to-br from-teal-50 to-cyan-50 rounded-lg">
    <div class="text-3xl mb-3">🔄</div>
    <div class="text-lg font-bold text-teal-600 mb-2">Iterative Refinement</div>
    <div class="text-sm text-gray-700">
      Build on previous responses
    </div>
    <div class="text-xs text-gray-500 mt-2 font-mono bg-white p-2 rounded">
      "Based on your previous response..."
    </div>
  </div>
</div>

---
layout: top-title-two-cols
align: c-lt-lt
columns: is-6
---

:: title ::

# ⚡ Advanced Prompting Methods

:: left ::

## 🧠 Tree of Thoughts
```
Explore 3 different approaches:
1. Approach A: [reasoning path]
2. Approach B: [reasoning path]  
3. Approach C: [reasoning path]

Evaluate each and choose the best
```

## 🎯 ReAct (Reasoning + Acting)
```
Thought: What do I need to find out?
Action: [specific step to take]
Observation: [what I learned]
Thought: What should I do next?
```

:: right ::

## 🔍 Self-Consistency
```
Generate 3 different solutions 
to this problem independently, 
then compare and synthesize 
the best elements from each.
```

## 📊 Structured Output
```json
{
  "analysis": "...",
  "confidence": 0.85,
  "alternatives": ["...", "..."],
  "next_steps": ["...", "..."]
}
```

<!--
Advanced techniques to cover:

1. Tree of Thoughts:
   - Exploring multiple reasoning paths
   - Evaluating different approaches
   - Synthesizing best solutions

2. ReAct (Reasoning and Acting):
   - Combining thinking and action steps
   - Iterative problem-solving approach
   - Tool use integration

3. Self-Consistency:
   - Multiple independent attempts
   - Voting/consensus mechanisms
   - Reliability improvement

4. Structured Output:
   - JSON formatting
   - Consistent data structures
   - API-friendly responses

5. Meta-prompting:
   - Prompts that generate prompts
   - Self-improving systems
   - Dynamic adaptation

Include hands-on examples for each technique
-->

---
layout: top-title
align: c
---

:: title ::

# 🛠️ Week 2 Activities & Assignments

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div class="activity-box">
    <div class="text-xl font-bold text-blue-600 mb-3">🎯 In-Class Activity</div>
    <div class="text-lg font-semibold mb-2">Prompt Engineering Challenge</div>
    <div class="text-sm text-gray-700">
      • Teams compete to create the best prompt for a complex task<br>
      • Given: A research question in various domains<br>
      • Goal: Generate comprehensive analysis<br>
      • Judge responses on quality, structure, insight<br>
      • Winning team presents their approach
    </div>
  </div>
  
  <div class="activity-box">
    <div class="text-xl font-bold text-green-600 mb-3">📋 Assignment</div>
    <div class="text-lg font-semibold mb-2">Technique Mastery Portfolio</div>
    <div class="text-sm text-gray-700">
      • Create 5 prompts, each using a different technique<br>
      • Apply to your academic/professional field<br>
      • Document the reasoning behind each design<br>
      • Include input prompt and AI response<br>
      • Reflect on effectiveness and limitations
    </div>
  </div>
</div>

<div class="mt-8 p-6 bg-purple-50 rounded-lg">
  <div class="text-xl font-bold text-purple-700 mb-3">🎯 Capstone Project - Phase 2</div>
  <div class="text-lg font-semibold mb-2">Develop Your Solution</div>
  <div class="text-gray-700">
    Create a comprehensive prompt strategy to address your chosen problem. Design a multi-step prompting approach using at least 3 different techniques. Test and iterate on your prompts.
  </div>
</div>

---
layout: center
class: text-center
---

# Week 3: Advanced Applications
## *Ethics, Complexity & the Future*

<div class="text-6xl mb-6">🚀</div>

<div class="grid grid-cols-2 gap-8 mt-8">
  <div class="text-left">
    <div class="text-2xl mb-4 font-semibold text-blue-500">🎓 Learning Objectives</div>
    <div class="space-y-2 text-lg">
      <div>• Master complex prompting scenarios</div>
      <div>• Understand ethical implications</div>
      <div>• Explore cutting-edge applications</div>
      <div>• Develop future-ready skills</div>
    </div>
  </div>
  
  <div class="text-left">
    <div class="text-2xl mb-4 font-semibold text-purple-500">⏰ Schedule (3 hours)</div>
    <div class="space-y-2 text-lg">
      <div>• 45min: Complex multi-step prompting</div>
      <div>• 45min: Ethics & responsible AI use</div>
      <div>• 45min: Cutting-edge applications</div>
      <div>• 45min: Capstone presentations</div>
    </div>
  </div>
</div>

---
layout: top-title
color: red-light
align: c
---

:: title ::

# 🎯 Complex Multi-Step Prompting

:: content ::

<div class="text-center mb-8">
  <div class="text-4xl mb-4">🧩 → 🔄 → 🎯 → 📊</div>
  <div class="text-xl text-gray-600">Decompose → Iterate → Synthesize → Validate</div>
</div>

<div class="grid grid-cols-2 gap-8 mt-6">
  <div class="p-6 bg-blue-50 rounded-lg">
    <div class="text-2xl font-bold text-blue-700 mb-4">📋 Research Pipeline</div>
    <div class="text-sm text-blue-600 space-y-2">
      <div><strong>Step 1:</strong> Literature review prompts</div>
      <div><strong>Step 2:</strong> Gap analysis and synthesis</div>
      <div><strong>Step 3:</strong> Hypothesis generation</div>
      <div><strong>Step 4:</strong> Methodology design</div>
      <div><strong>Step 5:</strong> Results interpretation</div>
    </div>
  </div>
  
  <div class="p-6 bg-green-50 rounded-lg">
    <div class="text-2xl font-bold text-green-700 mb-4">💼 Business Analysis</div>
    <div class="text-sm text-green-600 space-y-2">
      <div><strong>Step 1:</strong> Market analysis</div>
      <div><strong>Step 2:</strong> Competitive landscape</div>
      <div><strong>Step 3:</strong> SWOT analysis</div>
      <div><strong>Step 4:</strong> Strategic recommendations</div>
      <div><strong>Step 5:</strong> Implementation plan</div>
    </div>
  </div>
</div>

<div class="mt-8 p-6 bg-purple-50 rounded-lg text-center">
  <div class="text-xl font-bold text-purple-700 mb-2">🎯 Key Principle</div>
  <div class="text-lg text-purple-600">
    Complex tasks require decomposition, coordination, and validation across multiple AI interactions
  </div>
</div>

---
layout: top-title
color: amber-light
align: c
---

:: title ::

# ⚖️ Ethics & Responsible AI Use

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div class="p-6 bg-red-50 rounded-lg">
    <div class="text-2xl font-bold text-red-700 mb-4">🚨 Potential Risks</div>
    <div class="space-y-3 text-red-600">
      <div class="flex items-start">
        <div class="text-lg mr-2">📊</div>
        <div>
          <div class="font-semibold">Bias Amplification</div>
          <div class="text-sm">AI can perpetuate or amplify existing biases</div>
        </div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">🎭</div>
        <div>
          <div class="font-semibold">Academic Integrity</div>
          <div class="text-sm">Plagiarism and attribution concerns</div>
        </div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">🔐</div>
        <div>
          <div class="font-semibold">Privacy Issues</div>
          <div class="text-sm">Sensitive data in prompts</div>
        </div>
      </div>
    </div>
  </div>
  
  <div class="p-6 bg-green-50 rounded-lg">
    <div class="text-2xl font-bold text-green-700 mb-4">✅ Best Practices</div>
    <div class="space-y-3 text-green-600">
      <div class="flex items-start">
        <div class="text-lg mr-2">🎯</div>
        <div>
          <div class="font-semibold">Transparency</div>
          <div class="text-sm">Always disclose AI assistance used</div>
        </div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">🔍</div>
        <div>
          <div class="font-semibold">Verification</div>
          <div class="text-sm">Fact-check AI-generated content</div>
        </div>
      </div>
      <div class="flex items-start">
        <div class="text-lg mr-2">🧠</div>
        <div>
          <div class="font-semibold">Critical Thinking</div>
          <div class="text-sm">Use AI to enhance, not replace, analysis</div>
        </div>
      </div>
    </div>
  </div>
</div>

---
layout: top-title
color: indigo-light
align: c
---

:: title ::

# 🌟 Cutting-Edge Applications

:: content ::

<div class="grid grid-cols-3 gap-6 mt-6">
  <div class="text-center p-5 bg-gradient-to-br from-purple-50 to-indigo-50 rounded-lg">
    <div class="text-4xl mb-3">🔬</div>
    <div class="text-lg font-bold text-purple-600 mb-2">Scientific Discovery</div>
    <div class="text-sm text-gray-700">
      AI-assisted hypothesis generation, experimental design, and literature synthesis
    </div>
  </div>
  
  <div class="text-center p-5 bg-gradient-to-br from-blue-50 to-cyan-50 rounded-lg">
    <div class="text-4xl mb-3">📝</div>
    <div class="text-lg font-bold text-blue-600 mb-2">Academic Writing</div>
    <div class="text-sm text-gray-700">
      Structured arguments, citation analysis, and manuscript improvement
    </div>
  </div>
  
  <div class="text-center p-5 bg-gradient-to-br from-green-50 to-teal-50 rounded-lg">
    <div class="text-4xl mb-3">💼</div>
    <div class="text-lg font-bold text-green-600 mb-2">Professional Development</div>
    <div class="text-sm text-gray-700">
      Career planning, skill assessment, and interview preparation
    </div>
  </div>
  
  <div class="text-center p-5 bg-gradient-to-br from-orange-50 to-red-50 rounded-lg">
    <div class="text-4xl mb-3">🎨</div>
    <div class="text-lg font-bold text-orange-600 mb-2">Creative Projects</div>
    <div class="text-sm text-gray-700">
      Content creation, design thinking, and innovation workshops
    </div>
  </div>
  
  <div class="text-center p-5 bg-gradient-to-br from-pink-50 to-purple-50 rounded-lg">
    <div class="text-4xl mb-3">🤝</div>
    <div class="text-lg font-bold text-pink-600 mb-2">Collaboration</div>
    <div class="text-sm text-gray-700">
      Team facilitation, meeting summaries, and project coordination
    </div>
  </div>
  
  <div class="text-center p-5 bg-gradient-to-br from-yellow-50 to-orange-50 rounded-lg">
    <div class="text-4xl mb-3">📊</div>
    <div class="text-lg font-bold text-yellow-600 mb-2">Data Analysis</div>
    <div class="text-sm text-gray-700">
      Statistical interpretation, visualization guidance, and insight generation
    </div>
  </div>
</div>

---
layout: top-title
align: c
---

:: title ::

# 🎯 Final Activities & Capstone Projects

:: content ::

<div class="grid grid-cols-1 gap-8 mt-6">
  <div class="activity-box">
    <div class="text-xl font-bold text-blue-600 mb-3">🎯 Capstone Presentations</div>
    <div class="text-lg font-semibold mb-2">Student Project Showcase</div>
    <div class="text-sm text-gray-700 grid grid-cols-2 gap-4">
      <div>
        <strong>Presentation Format:</strong><br>
        • 10 minutes presentation<br>
        • 5 minutes Q&A<br>
        • Problem statement & solution<br>
        • Prompt strategy demonstration<br>
        • Results and lessons learned
      </div>
      <div>
        <strong>Evaluation Criteria:</strong><br>
        • Problem complexity & relevance<br>
        • Prompt engineering sophistication<br>
        • Ethical considerations addressed<br>
        • Practical applicability<br>
        • Presentation clarity
      </div>
    </div>
  </div>
</div>

<div class="mt-8 grid grid-cols-3 gap-6">
  <div class="p-4 bg-purple-50 rounded-lg text-center">
    <div class="text-2xl mb-2">🏆</div>
    <div class="font-bold text-purple-700">Innovation Award</div>
    <div class="text-sm text-gray-600">Most creative application</div>
  </div>
  <div class="p-4 bg-blue-50 rounded-lg text-center">
    <div class="text-2xl mb-2">⚡</div>
    <div class="font-bold text-blue-700">Technical Excellence</div>
    <div class="text-sm text-gray-600">Most sophisticated prompting</div>
  </div>
  <div class="p-4 bg-green-50 rounded-lg text-center">
    <div class="text-2xl mb-2">🌍</div>
    <div class="font-bold text-green-700">Impact Potential</div>
    <div class="text-sm text-gray-600">Greatest practical value</div>
  </div>
</div>

---
layout: top-title
color: emerald-light
align: c
---

:: title ::

# 📊 Capstone Project Examples

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div class="p-6 bg-blue-50 rounded-lg">
    <div class="text-xl font-bold text-blue-700 mb-3">🔬 Research Projects</div>
    <div class="space-y-3 text-sm">
      <div>
        <div class="font-semibold">Literature Review Assistant</div>
        <div class="text-gray-600">Multi-step prompting system for comprehensive academic research synthesis</div>
      </div>
      <div>
        <div class="font-semibold">Grant Proposal Generator</div>
        <div class="text-gray-600">Structured approach to research proposal development and refinement</div>
      </div>
      <div>
        <div class="font-semibold">Peer Review Analyzer</div>
        <div class="text-gray-600">AI system to help understand and respond to manuscript reviews</div>
      </div>
    </div>
  </div>
  
  <div class="p-6 bg-green-50 rounded-lg">
    <div class="text-xl font-bold text-green-700 mb-3">💼 Professional Projects</div>
    <div class="space-y-3 text-sm">
      <div>
        <div class="font-semibold">Career Development Coach</div>
        <div class="text-gray-600">Personalized guidance for academic and industry career paths</div>
      </div>
      <div>
        <div class="font-semibold">Teaching Assistant</div>
        <div class="text-gray-600">AI-powered help for course design and student engagement</div>
      </div>
      <div>
        <div class="font-semibold">Conference Presentation Optimizer</div>
        <div class="text-gray-600">System to improve presentation structure and impact</div>
      </div>
    </div>
  </div>
</div>

<div class="mt-8 p-6 bg-yellow-50 rounded-lg text-center">
  <div class="text-xl font-bold text-yellow-700 mb-2">💡 Project Requirements</div>
  <div class="text-gray-700">
    Each capstone must demonstrate mastery of at least 3 prompt engineering techniques, 
    address a real problem, include ethical considerations, and show measurable impact
  </div>
</div>

---
layout: top-title
color: purple-light
align: c
---

:: title ::

# 🚀 Future Trends & Opportunities

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div>
    <div class="text-2xl font-bold text-purple-700 mb-4">🔮 Emerging Capabilities</div>
    <div class="space-y-3">
      <div class="flex items-center">
        <div class="text-2xl mr-3">🎵</div>
        <div>
          <div class="font-semibold">Multimodal AI</div>
          <div class="text-sm text-gray-600">Text, images, audio, and video integration</div>
        </div>
      </div>
      <div class="flex items-center">
        <div class="text-2xl mr-3">🏃</div>
        <div>
          <div class="font-semibold">Real-time AI</div>
          <div class="text-sm text-gray-600">Instant responses and continuous learning</div>
        </div>
      </div>
      <div class="flex items-center">
        <div class="text-2xl mr-3">🔗</div>
        <div>
          <div class="font-semibold">AI Agents</div>
          <div class="text-sm text-gray-600">Autonomous task completion and workflow automation</div>
        </div>
      </div>
    </div>
  </div>
  
  <div>
    <div class="text-2xl font-bold text-blue-700 mb-4">💼 Career Opportunities</div>
    <div class="space-y-3">
      <div class="flex items-center">
        <div class="text-2xl mr-3">🎯</div>
        <div>
          <div class="font-semibold">Prompt Engineer</div>
          <div class="text-sm text-gray-600">Specialized role in AI system optimization</div>
        </div>
      </div>
      <div class="flex items-center">
        <div class="text-2xl mr-3">🤝</div>
        <div>
          <div class="font-semibold">AI Collaboration Specialist</div>
          <div class="text-sm text-gray-600">Bridge between humans and AI systems</div>
        </div>
      </div>
      <div class="flex items-center">
        <div class="text-2xl mr-3">⚖️</div>
        <div>
          <div class="font-semibold">AI Ethics Consultant</div>
          <div class="text-sm text-gray-600">Ensure responsible AI development and deployment</div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="mt-8 text-center">
  <div class="text-xl font-semibold text-gray-700 mb-2">🌟 The Key to Success</div>
  <div class="text-lg text-gray-600 max-w-3xl mx-auto">
    Continuous learning, ethical awareness, and creative application of AI capabilities
  </div>
</div>

---
layout: top-title
align: c
---

:: title ::

# 🎯 Course Summary & Key Takeaways

:: content ::

<div class="grid grid-cols-3 gap-6 mt-6">
  <div class="text-center p-6 bg-gradient-to-br from-red-50 to-pink-50 rounded-xl">
    <div class="text-4xl mb-3">🧠</div>
    <div class="text-lg mb-2 font-semibold">Technical Mastery</div>
    <div class="text-sm text-gray-600">Understanding AI fundamentals and prompt engineering techniques</div>
  </div>
  
  <div class="text-center p-6 bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl">
    <div class="text-4xl mb-3">⚖️</div>
    <div class="text-lg mb-2 font-semibold">Ethical Awareness</div>
    <div class="text-sm text-gray-600">Responsible AI use and understanding of limitations</div>
  </div>
  
  <div class="text-center p-6 bg-gradient-to-br from-green-50 to-emerald-50 rounded-xl">
    <div class="text-4xl mb-3">🚀</div>
    <div class="text-lg mb-2 font-semibold">Future Readiness</div>
    <div class="text-sm text-gray-600">Adaptability and continuous learning mindset</div>
  </div>
</div>

<div class="mt-8 p-6 bg-purple-50 rounded-lg">
  <div class="text-2xl font-bold text-purple-700 mb-4 text-center">📈 Learning Outcomes Achieved</div>
  <div class="grid grid-cols-2 gap-4 text-sm">
    <div>
      <div class="font-semibold text-purple-600 mb-2">Technical Skills:</div>
      <div class="space-y-1 text-gray-700">
        <div>✅ Transformer architecture understanding</div>
        <div>✅ Core prompt engineering techniques</div>
        <div>✅ Advanced multi-step prompting</div>
        <div>✅ Complex problem decomposition</div>
      </div>
    </div>
    <div>
      <div class="font-semibold text-purple-600 mb-2">Professional Skills:</div>
      <div class="space-y-1 text-gray-700">
        <div>✅ AI-human collaboration</div>
        <div>✅ Ethical decision making</div>
        <div>✅ Critical evaluation of AI outputs</div>
        <div>✅ Continuous learning strategies</div>
      </div>
    </div>
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
`your.email@university.edu`

<div class="text-xl italic mt-8 text-gray-600">
"The future belongs to those who can dance with AI, not compete against it."
</div>

---
layout: top-title
---

:: title ::

# 📚 Resources & Further Learning

:: content ::

<div class="grid grid-cols-2 gap-8 mt-6">
  <div>
    <div class="text-xl font-bold text-blue-700 mb-4">📖 Essential Reading</div>
    <div class="text-sm space-y-2">
      <div>• "Attention Is All You Need" - Transformer paper</div>
      <div>• "Language Models are Few-Shot Learners" - GPT-3 paper</div>
      <div>• "The Prompt Report" - Comprehensive prompting guide</div>
      <div>• "AI and the Future of Work" - Brynjolfsson & Mitchell</div>
      <div>• "Human Compatible" - Stuart Russell</div>
    </div>
  </div>
  
  <div>
    <div class="text-xl font-bold text-green-700 mb-4">🛠️ Tools & Platforms</div>
    <div class="text-sm space-y-2">
      <div>• <strong>ChatGPT</strong> - OpenAI's conversational AI</div>
      <div>• <strong>Claude</strong> - Anthropic's AI assistant</div>
      <div>• <strong>Prompt Engineering Guide</strong> - Online resource</div>
      <div>• <strong>LangChain</strong> - AI application framework</div>
      <div>• <strong>Weights & Biases</strong> - ML experiment tracking</div>
    </div>
  </div>
</div>

<div class="mt-8 p-6 bg-gray-50 rounded-lg">
  <div class="text-xl font-bold text-gray-700 mb-3">🔗 Online Communities</div>
  <div class="grid grid-cols-3 gap-4 text-sm">
    <div>
      <div class="font-semibold">Reddit</div>
      <div class="text-gray-600">r/MachineLearning<br>r/ChatGPT</div>
    </div>
    <div>
      <div class="font-semibold">Discord</div>
      <div class="text-gray-600">OpenAI Community<br>AI Research Groups</div>
    </div>
    <div>
      <div class="font-semibold">Twitter/X</div>
      <div class="text-gray-600">AI researchers<br>#PromptEngineering</div>
    </div>
  </div>
</div>

---
layout: center
class: text-center
---

# Thank You

<div class="text-6xl mb-8">🙏</div>

<div class="pt-8">
  <span class="px-4 py-2 rounded cursor-pointer text-lg" hover="bg-white bg-opacity-10">
    Ready to shape the future with AI? Let's get started! 🚀
  </span>
</div>