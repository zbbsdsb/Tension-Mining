<p align="center">
  <img src="./assets/logo.svg" alt="Tension Mining" width="64" height="64" style="vertical-align: middle; margin-right: 12px;">
  <img src="./social-preview.jpg" alt="Tension Mining" width="100%">
</p>

<p align="center">
  <a href="https://github.com/zbbsdsb/Tension-Mining/stargazers"><img src="https://img.shields.io/github/stars/zbbsdsb/Tension-Mining?style=flat-square&color=e63946" alt="GitHub Stars"></a>
  <a href="https://github.com/zbbsdsb/Tension-Mining/network/members"><img src="https://img.shields.io/github/forks/zbbsdsb/Tension-Mining?style=flat-square&color=f4a261" alt="GitHub Forks"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square&color=2a9d8f" alt="MIT License"></a>
  <a href="./SKILL.md"><img src="https://img.shields.io/badge/skill-v2.0-blue?style=flat-square&color=4a6fa5" alt="Skill v2.0"></a>
  <a href="./references/tension-atlas.md"><img src="https://img.shields.io/badge/tensions-19-4a6fa5?style=flat-square" alt="19 Tensions"></a>
  <a href="./references/invariant-atlas.md"><img src="https://img.shields.io/badge/invariants-12-4a6fa5?style=flat-square" alt="12 Invariants"></a>
  <a href="./examples/"><img src="https://img.shields.io/badge/cases-11_studies-6b7280?style=flat-square" alt="11 Case Studies"></a>
  <a href="https://github.com/zbbsdsb/Tension-Mining/actions"><img src="https://img.shields.io/github/actions/workflow/status/zbbsdsb/Tension-Mining/ci.yml?style=flat-square&color=2a9d8f" alt="CI Status"></a>
</p>

---

<p align="center">
  <a href="./README.md">English</a> | <a href="./README.zh-CN.md">简体中文</a> | <a href="./README.es.md">Español</a> | हिन्दी
</p>

<p align="center">
  <strong>
    ⭐ इस रेपो को स्टार करें &nbsp;·&nbsp;
    <a href="https://github.com/zbbsdsb/Tension-Mining/discussions">💬 चर्चा</a> &nbsp;·&nbsp;
    <a href="https://twitter.com/intent/tweet?text=Tension%20Mining%20%E2%80%94%20Discover%20cross-domain%20invariants%20in%20complex%20systems&url=https://github.com/zbbsdsb/Tension-Mining">🐦 Twitter पर साझा करें</a>
  </strong>
</p>

---

> **अधिकांश लोग समाधान खोजते हैं। महान शोधकर्ता तनाव खोजते हैं।**

एक शोध पद्धति जो जटिल सिस्टमों के अंदर छिपे Invariant को खोजने का काम करती है। यह **AI-निष्पादन योग्य Skill** के रूप में Claude Code, TRAE, Cursor, Windsurf, और उन सभी टूल्स पर काम करती है जो Markdown-आधारित Skill फ़ाइलों को सपोर्ट करते हैं।

[त्वरित आरंभ](#त्वरित-आरंभ) · [यह कैसे काम करता है](#यह-कैसे-काम-करता-है) · [केस स्टडीज़](#केस-स्टडीज़) · [दस्तावेज़ीकरण](#दस्तावेज़ीकरण) · [योगदान करें](./CONTRIBUTING.md)

---

## विषय सूची

- [Tension Mining क्यों?](#tension-mining-क्यों)
- [त्वरित आरंभ](#त्वरित-आरंभ)
- [यह कैसे काम करता है](#यह-कैसे-काम-करता-है)
- [सात चरण](#सात-चरण)
- [केस स्टडीज़](#केस-स्टडीज़)
- [यह क्या नहीं है](#यह-क्या-नहीं-है)
- [दस्तावेज़ीकरण](#दस्तावेज़ीकरण)
- [रोडमैप](#रोडमैप)
- [लाइसेंस](#लाइसेंस)

---

## Tension Mining क्यों?

अधिकांश नवाचार कार्यप्रवाह बहुत देर से शुरू होते हैं।

वे एल्गोरिदम, आर्किटेक्चर, कार्यान्वयन, ऑप्टिमाइज़ेशन से शुरू होते हैं। लेकिन सबसे प्रभावशाली सिस्टम शायद ही कभी ऑप्टिमाइज़ेशन से उभरते हैं।

- **PageRank** — एक मैट्रिक्स समीकरण से नहीं, बल्कि 'महत्व' के बारे में एक प्रश्न से शुरू हुआ।
- **Bitcoin** — एक ब्लॉकचेन डेटा संरचना से नहीं, बल्कि विकेंद्रीकरण और विश्वास के बीच तनाव से शुरू हुआ।
- **Wikipedia** — एक रिवीज़न नियंत्रण प्रणाली से नहीं, बल्कि खुलेपन और विश्वसनीयता के बीच तनाव से शुरू हुआ।
- **Transformer** — एक अटेंशन मैकेनिज्म से नहीं, बल्कि इस प्रश्न से शुरू हुआ कि क्या रिकरेंस वास्तव में आवश्यक था।

सफलता एल्गोरिदम से बहुत पहले प्रकट होती है। यह तब प्रकट होती है जब एक छिपा हुआ तनाव अंततः दृश्यमान हो जाता है।

**Tension Mining एक लेंस है।** इसका उद्देश्य सरल है: शोधकर्ताओं को सिस्टम को डिज़ाइन करने का प्रयास करने से पहले, सिस्टम को आकार देने वाली ताकतों की खोज करने में मदद करना।

### मुख्य विचार

हर स्थायी सिस्टम अनसुलझे तनावों के एक समूह द्वारा आकार दिया जाता है।

| डोमेन | तनाव |
|--------|---------|
| संगठन | स्वतंत्रता ↔ दक्षता |
| समाज | व्यवस्था ↔ नवाचार |
| AI एजेंट | स्वायत्तता ↔ नियंत्रण |
| NPC दुनिया | अस्तित्व ↔ अन्वेषण |
| उत्पाद | सरलता ↔ क्षमता |
| बाजार | प्रतिस्पर्धा ↔ सहयोग |

अधिकांश लोग व्यवहार पर ध्यान केंद्रित करते हैं। Tension Mining व्यवहार के नीचे की ताकतों पर ध्यान केंद्रित करती है।

---

## शैक्षणिक आधार

Tension Mining कई स्थापित शोध परंपराओं से अवधारणाओं को ग्रहण और संश्लेषित करती है।

| क्षेत्र | प्रमुख संदर्भ | संबंध |
|---------|--------------|--------|
| जटिल प्रणाली | Mitchell (2009) [1], Holland (1995) [2] | उद्भव, स्व-संगठन और अनुकूलन के लिए मुख्य ढाँचा |
| डिज़ाइन थिंकिंग | Schön (1983) [3], Cross (2006) [4] | घटना-प्रथम दृष्टिकोण, समाधान से पहले समस्या का पुनर्निर्धारण |
| सिस्टम्स थिंकिंग | Meadows (2008) [5], Senge (1990) [6] | फीडबैक लूप, लीवरेज पॉइंट, सिस्टम संरचना विश्लेषण |
| साइनेफ़िन ढाँचा | Snowden & Boone (2007) [7] | क्रमबद्ध बनाम जटिल समस्या डोमेन में अंतर करना |
| शोध पद्धति | Kuhn (1962) [8], Lakatos (1970) [9] | प्रतिमान बदलाव, शोध कार्यक्रम संरचना, मिथ्याकरण |
| विकासवादी सिद्धांत | Dawkins (1976) [10], Boyd & Richerson (1985) [11] | भिन्नता-चयन-प्रतिधारण इनवेरिएंट खोज इंजन के रूप में |
| नेटवर्क विज्ञान | Barabási & Albert (1999) [12], Watts & Strogatz (1998) [13] | स्थानीय अंतःक्रियाओं से उद्भवशील गुण, छोटी-दुनिया की घटनाएँ |

ये आधार केवल सजावट नहीं हैं। प्रत्येक सीधे पाइपलाइन के एक विशिष्ट चरण को सूचित करता है:
- **जटिल प्रणाली** → चरण 1 (घटनाओं को डोमेन पार करना चाहिए, डोमेन अदूरदर्शिता को मजबूत नहीं करना चाहिए)
- **डिज़ाइन थिंकिंग** → चरण 2-3 (समाधान से पहले तनाव, मुख्य कौशल के रूप में पुनर्निर्धारण)
- **सिस्टम्स थिंकिंग** → चरण 4-5 (तंत्र फीडबैक के माध्यम से परस्पर क्रिया करते हैं, रैखिक कारणता से नहीं)
- **साइनेफ़िन** → चरण 7 (विनाश यह प्रकट करता है कि समस्या जटिल या पेचीदा डोमेन में थी)
- **विकासवादी सिद्धांत** → चरण 3 (इनवेरिएंट क्रॉस-डोमेन उत्तरजीविता द्वारा चुने जाते हैं, डिज़ाइनर के इरादे से नहीं)

विस्तृत तुलना और पूर्ण पठन सूची के लिए [पद्धति प्राइमर](./references/methodology-primer.md) देखें।

---

## त्वरित आरंभ

### 1. इंस्टॉल करें

इस रिपॉजिटरी को अपने AI टूल की Skill निर्देशिका में क्लोन करें:

```bash
# Claude Code — प्रोजेक्ट स्तर (अनुशंसित)
git clone https://github.com/zbbsdsb/Tension-Mining.git .claude/skills/tension-mining

# Claude Code — उपयोगकर्ता स्तर (सभी प्रोजेक्ट)
git clone https://github.com/zbbsdsb/Tension-Mining.git ~/.claude/skills/tension-mining

# TRAE
git clone https://github.com/zbbsdsb/Tension-Mining.git .trae/skills/tension-mining

# Cursor / Windsurf / अन्य
# रिपॉजिटरी को कहीं भी सुलभ स्थान पर रखें। अपने प्रोजेक्ट निर्देशों में SKILL.md का संदर्भ दें।
```

### 2. उपयोग करें

**स्वचालित ट्रिगर** — एक जटिल सिस्टम समस्या का प्राकृतिक भाषा में वर्णन करें:

> "मैं एक P2P मार्केटप्लेस के लिए विकेंद्रीकृत पहचान प्रणाली डिज़ाइन करना चाहता हूँ।"

AI ट्रिगर का पता लगाता है और स्वचालित रूप से Tension Mining को सक्रिय करता है।

**मैन्युअल ट्रिगर** — Skill को सीधे आमंत्रित करें:

| टूल | कमांड |
|------|---------|
| Claude Code | `/tension-mining` |
| TRAE | AI `SKILL.md` विवरण के आधार पर स्वतः सक्रिय होता है |
| Cursor / Windsurf | अपने `.cursorrules` या प्रोजेक्ट निर्देशों में `SKILL.md` का संदर्भ दें |

### 3. 7 चरणों का पालन करें

AI आपको 7 चरणों के माध्यम से मार्गदर्शन करेगा, हर बार एक प्रश्न पूछते हुए:

```
1. Phenomenon Mining  →  3+ डोमेन से 5-10 वास्तविक उदाहरण एकत्र करें
2. Tension Mining      →  5+ अपरिहार्य समझौतों की पहचान करें
3. Invariant Mining    →  3+ क्रॉस-डोमेन सिद्धांत निकालें
4. Mechanism Mining    →  अध्ययन करें कि वास्तविकता इन तनावों को कैसे हल करती है
5. System Synthesis    →  एक सुसंगत मॉडल में संयोजित करें
6. Algorithm Synthesis →  तंत्रों से एल्गोरिदम व्युत्पन्न करें (केवल अब)
7. Destruction Phase   →  अपने स्वयं के मॉडल पर हमला करें
```

**मुख्य सिद्धांत:** समाधानों से शुरू न करें। वास्तविकता से शुरू करें।

---

## यह कैसे काम करता है

### डिज़ाइन पैटर्न

Tension Mining **Pipeline + Inversion + Generator** हाइब्रिड पैटर्न का उपयोग करती है:

- **Pipeline** — 7 चरण सख्त क्रम में निष्पादित होते हैं। प्रत्येक चरण की एक गेट शर्त (Gate Condition) होती है; जब तक यह पूरी नहीं हो जाती, आप आगे नहीं बढ़ सकते।
- **Inversion** — AI चरण-दर-चरण आपका साक्षात्कार करता है, एक बार में एक प्रश्न पूछता है। आप सामग्री संचालित करते हैं; AI पद्धति लागू करता है।
- **Generator** — आउटपुट परिभाषित अनुभागों के साथ एक संरचित टेम्पलेट का पालन करता है, जो पूर्णता सुनिश्चित करता है।

### एंटी-चीट तंत्र

- **सामान्य तर्कसंगतता तालिका** — AI की चरणों को छोड़ने की प्रवृत्ति का प्रतिकार करती है ("मैं तनाव पहले से जानता हूँ, चलो सीधे एल्गोरिदम पर चलते हैं")
- **लाल झंडे** — ऐसे देखने योग्य व्यवहार जो इंगित करते हैं कि पद्धति का उल्लंघन हो रहा है
- **गुणवत्ता रूब्रिक** — 5-आयामी स्व-मूल्यांकन (D1-D5, स्कोर 0-15) प्रत्येक आउटपुट से जुड़ा हुआ

### प्रगतिशील प्रकटीकरण

`SKILL.md` एक संक्षिप्त सक्रियण कंकाल (~80 पंक्तियाँ) है। विस्तृत चरण निर्देश, एटलस और टेम्पलेट आवश्यकतानुसार लोड किए जाते हैं, जिससे प्रारंभिक संदर्भ न्यूनतम रहता है।

---

## सात चरण

### 1. Phenomenon Mining

> कौन से सिस्टम पहले से यह व्यवहार प्रदर्शित करते हैं?

अमूर्तता बनाने से पहले वास्तविकता का निरीक्षण करें। चींटी कालोनियों, कंपनियों, शहरों, पारिस्थितिकी तंत्रों, ऑनलाइन समुदायों, ओपन सोर्स प्रोजेक्ट्स से एक Phenomenon लाइब्रेरी बनाएं।

### 2. Tension Mining

> कौन सा समझौता कभी पूरी तरह समाप्त नहीं किया जा सकता?

सिस्टम को विभिन्न दिशाओं में खींचने वाली ताकतों की पहचान करें। एक तनाव मानचित्र (Tension Map) बनाएं।

### 3. Invariant Mining

> डोमेन की परवाह किए बिना क्या सत्य रहता है?

असंबंधित सिस्टमों में दिखाई देने वाले पैटर्न खोजें। Invariant निकालें।

### 4. Mechanism Mining

> प्रकृति, समाज या प्रौद्योगिकी में पहले से क्या तंत्र मौजूद हैं?

अध्ययन करें कि वास्तविकता तनावों को कैसे हल करती है। एक तंत्र लाइब्रेरी बनाएं।

### 5. System Synthesis

> सबसे छोटा मॉडल क्या है जो सिस्टम की व्याख्या करता है?

तनावों, Invariant और तंत्रों को एक सुसंगत मॉडल में संयोजित करें। पहचानें कि कौन से तनाव प्राथमिक हैं, कौन से तंत्र आवश्यक हैं, और कौन से विफलता मोड मौजूद हैं।

### 6. Algorithm Synthesis

> यदि तंत्र वास्तविक है, तो इसे कैसे लागू किया जाना चाहिए?

केवल अब एल्गोरिदम डिज़ाइन करें। उन्हें तंत्रों से स्वाभाविक रूप से उभरने दें।

### 7. Destruction Phase

> कौन सी मान्यताएँ विफल होती हैं? कौन से किनारे के मामले सिस्टम को तोड़ते हैं?

मॉडल पर हमला करें। मान लें कि यह गलत है। कमज़ोर मान्यताओं, लापता तनावों और संभावित पुनर्डिज़ाइन की पहचान करें।

---

## केस स्टडीज़

प्रत्येक केस स्टडी पूर्ण 7-चरणीय Pipeline से गुज़रती है:

| केस स्टडी | डोमेन | Key Tensions | Key Invariants |
|-----------|--------|-------------|----------------|
| [PageRank](./examples/page-rank.md) | सूचना पुनर्प्राप्ति | Local vs Global, Freedom vs Efficiency | Local Rules Create Global Order, Gradients Drive Movement |
| [Transformer](./examples/transformer.md) | गहन शिक्षण | Synchronicity vs Asynchronicity, Compression vs Fidelity | Compression Reveals Structure, Gradients Drive Movement |
| [Bitcoin](./examples/bitcoin.md) | क्रिप्टोकरेंसी | Centralization vs Decentralization, Competition vs Cooperation | Identity Drives Cooperation, Tradeoffs Are Inescapable |
| [Git](./examples/git.md) | संस्करण नियंत्रण | Consistency vs Availability, Local vs Global | Local Rules Create Global Order, Identity Drives Cooperation |
| [Wikipedia](./examples/wikipedia.md) | सहयोगात्मक ज्ञान | Freedom vs Efficiency, Individual vs Collective | Identity Drives Cooperation, Compression Reveals Structure |
| [NPC Society](./examples/npc-society.md) | मल्टी-एजेंट सिस्टम | Survival vs Exploration, Individual vs Collective | Local Rules Create Global Order, Variation Enables Selection |
| [Agent Organization](./examples/agent-organization.md) | AI समन्वय | Autonomy vs Control, Centralization vs Decentralization | Identity Drives Cooperation, Feedback Loops Stabilize |
| [Dialogue Walkthrough](./examples/dialogue-example.md) | विकेंद्रीकृत पहचान | *पूर्ण 7-चरण इंटरैक्शन डेमो* | *अनुशंसित पहला पठन* |
| [Consensus Protocols](./examples/consensus-protocols.md) | वितरित सिस्टम | Safety vs Liveness, Consistency vs Availability | Local Rules Create Global Order, Tradeoffs Are Inescapable |
| [Ant Colony Foraging](./examples/ant-colony.md) | जैविक सिस्टम | Individual vs Collective, Survival vs Exploration | Local Rules Create Global Order, Variation Enables Selection |
| [Market Efficiency](./examples/market-efficiency.md) | अर्थशास्त्र | Order vs Innovation, Competition vs Cooperation | Preferential Attachment, Tradeoffs Are Inescapable |

---

## यह क्या नहीं है

- **नहीं** एक प्रॉम्प्ट संग्रह
- **नहीं** एक विचार-मंथन टेम्पलेट
- **नहीं** एक उत्पादकता फ्रेमवर्क
- **नहीं** नवाचार का एक गारंटीकृत मार्ग
- **नहीं** एक विज़ुअल डिज़ाइन सिस्टम

Tension Mining एक लेंस है। इसका उद्देश्य सरल है: शोधकर्ताओं को सिस्टम को डिज़ाइन करने का प्रयास करने से पहले, सिस्टम को आकार देने वाली ताकतों की खोज करने में मदद करना।

---

## दस्तावेज़ीकरण

| पथ | उद्देश्य |
|------|---------|
| [`SKILL.md`](./SKILL.md) | सक्रियण कंकाल — AI प्रवेश बिंदु (~80 पंक्तियाँ) |
| [`references/execution-protocol.md`](./references/execution-protocol.md) | विस्तृत 7-चरण निर्देश (लक्ष्य / साक्षात्कार / आउटपुट / गेट) |
| [`references/interface-contract.md`](./references/interface-contract.md) | इनपुट/आउटपुट विनिर्देश और त्रुटि प्रबंधन |
| [`references/quality-rubric.md`](./references/quality-rubric.md) | 5-आयामी स्कोरिंग रूब्रिक (D1-D5, 0-15 पैमाना) |
| [`references/tension-atlas.md`](./references/tension-atlas.md) | 5 डोमेन में 19 स्थायी तनावों की सूची |
| [`references/invariant-atlas.md`](./references/invariant-atlas.md) | 4 परतों में 12 क्रॉस-डोमेन Invariant की सूची |
| [`references/methodology-primer.md`](./references/methodology-primer.md) | विस्तृत पद्धति संदर्भ और FAQ |
| [`examples/dialogue-example.md`](./examples/dialogue-example.md) | पूर्ण उपयोगकर्ता-AI संवाद वॉकथ्रू (**अनुशंसित पहला पठन**) |
| [`examples/`](./examples/) | 10 अतिरिक्त केस स्टडीज़ |
| [`templates/_core-template.md`](./templates/_core-template.md) | साझा 7-चरण कार्यप्रवाह कंकाल |
| [`templates/`](./templates/) | 9 डोमेन-विशिष्ट टेम्पलेट (एल्गोरिदम, AI एजेंट, NPC समाज, संगठन, प्रोटोकॉल, API डिज़ाइन, सर्वसम्मति प्रोटोकॉल, गेम डिज़ाइन) |
| [`PROJECT_STRUCTURE.md`](./PROJECT_STRUCTURE.md) | निर्देशिका लेआउट, निर्भरता ग्राफ, शासन नियम |
| [`CONTRIBUTING.md`](./CONTRIBUTING.md) | तनाव, Invariant, केस और टेम्पलेट कैसे योगदान करें |
| [`CHANGELOG.md`](./CHANGELOG.md) | संस्करण इतिहास |

---

## रोडमैप

### v2.0 (वर्तमान)
- [x] गेट शर्तों के साथ 7-चरण Pipeline
- [x] प्रगतिशील प्रकटीकरण आर्किटेक्चर
- [x] [CORE]/[EXPERIMENTAL] लेबलिंग के साथ एटलस
- [x] 9 डोमेन-विशिष्ट टेम्पलेट
- [x] 8 केस स्टडीज़
- [x] गुणवत्ता रूब्रिक (D1-D5)
- [x] स्वचालित एटलस सत्यापन के साथ CI/CD
- [x] एंटी-रेशनलाइज़ेशन रक्षा तंत्र

### v2.1 (योजनाबद्ध)
- [ ] इंटरैक्टिव वेब डेमो
- [x] अतिरिक्त केस स्टडीज़ (वितरित सिस्टम, जैविक सिस्टम, अर्थशास्त्र)
- [x] टेम्पलेट विस्तार (API डिज़ाइन, सर्वसम्मति प्रोटोकॉल, गेम डिज़ाइन)
- [ ] सामुदायिक-योगदानित तनाव और Invariant
- [x] बहुभाषी समर्थन (चीनी, स्पेनिश, हिंदी)

---

## एक प्रश्न

कुछ भी डिज़ाइन करने से पहले, पूछें:

> मैं वास्तव में किस तनाव को देख रहा हूँ?

उत्तर अक्सर एल्गोरिदम से अधिक मूल्यवान होता है।

---

## लाइसेंस

MIT License — Copyright (c) 2026 zbbsdsb

विवरण के लिए [LICENSE](./LICENSE) देखें।

---

## अनुवाद में योगदान करें

यदि आप Tension Mining में अन्य भाषाओं के अनुवाद योगदान करना चाहते हैं, तो कृपया PR सबमिट करें! निम्नलिखित पैटर्न का पालन करने की सलाह दी जाती है:
- `README.md` को कॉपी करें और `README.{भाषा-कोड}.md` के रूप में नाम बदलें
- सभी आंतरिक लिंक मूल अंग्रेज़ी फ़ाइलों की ओर इंगित रखें
- कोड ब्लॉक और फ़ाइल पथ यथावत रखें