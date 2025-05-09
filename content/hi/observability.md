---
title: ऑब्जर्वेबिलिटी (Observability)
status: Completed
category: संकल्पना
tags: ["property", "", ""]
---

## यह क्या है
अवलोकनीयता अवलोकन के तहत सिस्टम से संकेतों के आधार पर कार्रवाई योग्य अंतर्दृष्टि को लगातार उत्पन्न करने और खोजने की क्षमता है। दूसरे शब्दों में, अवलोकनीयता उपयोगकर्ताओं को बाहरी आउटपुट से सिस्टम की स्थिति को समझने और (सुधारात्मक) कार्रवाई करने की अनुमति देती है।

## समस्या
कंप्यूटर सिस्टम को निम्न-स्तरीय संकेतों जैसे सीपीयू समय, मेमोरी, डिस्क स्थान, और उच्च-स्तरीय और व्यावसायिक संकेतों को देखकर मापा जाता है, जिसमें एपीआई प्रतिक्रिया समय, त्रुटियां, प्रति सेकंड लेनदेन आदि शामिल हैं।

किसी प्रणाली की अवलोकनीयता का उसके परिचालन और विकास लागतों पर महत्वपूर्ण प्रभाव पड़ता है। ऑब्जर्वेबल सिस्टम अपने ऑपरेटरों को सार्थक, कार्रवाई योग्य डेटा प्रदान करते हैं, जिससे उन्हें अनुकूल परिणाम (त्वरित घटना प्रतिक्रिया, डेवलपर उत्पादकता में वृद्धि) और कम मेहनत और डाउनटाइम प्राप्त करने की अनुमति मिलती है।

## समाधान
यह समझना महत्वपूर्ण है कि अधिक जानकारी आवश्यक रूप से अधिक अवलोकन योग्य प्रणाली में परिवर्तित नहीं होती है। वास्तव में, कभी-कभी, सिस्टम द्वारा उत्पन्न जानकारी की मात्रा एप्लिकेशन द्वारा उत्पन्न शोर से मूल्यवान स्वास्थ्य संकेतों की पहचान करना कठिन बना सकती है। अवलोकनीयता के लिए सही निर्णय लेने के लिए सही उपभोक्ता (मानव या सॉफ़्टवेयर का टुकड़ा) के लिए सही समय पर सही डेटा की आवश्यकता होती है।
