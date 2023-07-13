# अक्सर पूछे जाने वाले प्रश्न

## सुझाए गए शब्द अंग्रेजी में क्यों हैं?

AiShort गैर-देशी अंग्रेजी बोलने वालों द्वारा ChatGPT के उपयोग की सुविधा के लिए बनाया गया था। हालाँकि, सभी सुझाए गए शब्द अंग्रेजी में हैं। ऐसा इसलिए है क्योंकि ChatGPT को अन्य भाषाओं की तुलना में अंग्रेजी की बेहतर समझ है। यहां तक कि मॉस, पहला बड़े पैमाने पर चीनी संवाद भाषा मॉडल, स्वीकार करता है कि इसकी अंग्रेजी प्रतिक्रियाएं चीनी से बेहतर हैं। इसलिए, अंग्रेजी सुझाए गए शब्दों का उपयोग करने की सिफारिश की जाती है। (MOSS अब उपलब्ध नहीं है)

यद्यपि गैर-अंग्रेजी सुझाए गए शब्दों का उपयोग करने से अच्छे परिणाम मिल सकते हैं, लेकिन जब आप उसी गैर-अंग्रेजी संकेतों को फिर से इनपुट करते हैं तो परिणाम काफी भिन्न हो सकते हैं। चूंकि चैटजीपीटी की गैर-अंग्रेजी संकेतों की समझ हर बार बदलती रहती है, इसलिए वांछित आउटपुट सुनिश्चित करने के लिए उत्पादकता-उन्मुख संकेतों के लिए अंग्रेजी संकेतों का उपयोग करने की सलाह दी जाती है। इसके अलावा, अंग्रेजी संकेतों द्वारा उत्पन्न प्रतिक्रियाएं अंग्रेजी में होने की संभावना है। आप प्रॉम्प्ट के अंत में "चीनी में प्रतिक्रिया" जोड़कर प्रतिक्रिया भाषा को चीनी के रूप में निर्दिष्ट कर सकते हैं। यदि आपकी मूल भाषा अलग है, तो कृपया "चीनी" को अपनी मूल भाषा से बदलें।

## क्या मुझे हर बार प्रॉम्प्ट इनपुट करना होगा?

एपीआई में, आप प्रॉम्प्ट को "सिस्टम प्रॉम्प्ट" के रूप में सेट कर सकते हैं, इसलिए आपको हर बार प्रॉम्प्ट इनपुट करने की आवश्यकता नहीं है। ChatGPT सिस्टम प्रॉम्प्ट के आधार पर निर्देशों का पालन करेगा।

ChatGPT के वेब संस्करण में, यदि आपने मुख्य प्रॉम्प्ट स्विच नहीं किया है, तो आप बस उद्धरण चिह्नों में बाद की उत्तर सामग्री को संलग्न कर सकते हैं, जिससे हर बार प्रॉम्प्ट इनपुट करने की आवश्यकता समाप्त हो जाती है। जब जेनरेट की गई प्रतिक्रिया शीघ्र आवश्यकताओं के साथ संरेखित नहीं होती है, तो इसका मतलब है कि चैटजीपीटी प्रॉम्प्ट भूल गया है, और ऐसे मामलों में, आपको इसे पुन: उन्मुख करने के लिए प्रॉम्प्ट को फिर से दर्ज करने की आवश्यकता है। इसके अतिरिक्त, प्रत्येक वार्तालाप लिंक अद्वितीय है, और आप अक्सर उपयोग किए जाने वाले वार्तालापों को भविष्य के उपयोग के लिए बुकमार्क के रूप में सहेज सकते हैं।

## इनपुट विधि खोज में देरी

खोज फ़ंक्शन डोक्यूसॉरस के प्रदर्शन पर आधारित है और इसमें पीसी पक्ष पर ध्यान खोने वाली इनपुट विधि के साथ एक समस्या है। डोक्यूसॉरस को इस मुद्दे की रिपोर्ट करने के बाद, उन्होंने उल्लेख किया कि वे इसे ठीक करने की कोशिश करेंगे, लेकिन अब तक, समस्या अनसुलझी बनी हुई है, टिप्पणी के साथ, "एफडब्ल्यूआईडब्ल्यू, आपको वैसे भी चीनी का उपयोग नहीं करना चाहिए, क्योंकि शोकेस स्थानीयकृत नहीं है। इसलिए, मैंने खोज घटक को दो प्रकारों में वर्गीकृत किया है: मोबाइल और पीसी। मोबाइल के लिए खोज तर्क अपरिवर्तित रहता है, जबकि 768 पीएक्स से ऊपर स्क्रीन चौड़ाई सीमा के साथ पीसी ब्राउज़िंग के लिए, मैंने इनपुट विधि समस्या को संबोधित करने के लिए "डिबाउंस" फ़ंक्शन पेश किया है। हालांकि, यह पीसी पक्ष पर दो मुद्दों का परिचय देता है: गैर-अंग्रेजी इनपुट को 800 मिलीसेकंड के भीतर पूरा करने की आवश्यकता होती है, और पीसी खोज ताज़ा त्वरित से 800-मिलीसेकंड की देरी में बदल जाती है। यदि आपके पास बेहतर समाधान है, तो कृपया प्रतिक्रिया प्रदान करें।

## झूठी जानकारी देना

हालांकि ChatGPT बहुत शक्तिशाली है, यह अचूक नहीं है। कभी-कभी यह गलत जानकारी दे सकता है। उदाहरण के लिए, जब मुझे एआईशॉर्ट में जानकारी के सैकड़ों टुकड़े इनपुट करने की आवश्यकता थी, तो मेरे पास चैटजीपीटी डेटा को एक निर्दिष्ट प्रारूप में परिवर्तित कर रहा था। हालांकि, रूपांतरण प्रक्रिया के दौरान, मैंने देखा कि ChatGPT ने कुछ जानकारी गलत तरीके से लिखी थी। उदाहरण के लिए, पाठ में एक लेबल "फिल्म आलोचक" था, लेकिन ChatGPT ने इसे "फिल्म आलोचक" में बदल दिया। हालांकि इसका पाठ में कोई प्रभाव नहीं हो सकता है, लेकिन कोड में उपयोग किए जाने पर यह त्रुटि का कारण होगा। इसलिए, ChatGPT का उपयोग करते समय, इसके आउटपुट की समीक्षा करना आवश्यक है।

## सुझाए गए शब्द अच्छी तरह से काम नहीं कर रहे हैं

सभी सुझाए गए शब्द इंटरनेट से प्राप्त किए जाते हैं और नियमित रूप से अपडेट किए जाते हैं। यद्यपि मैंने प्रत्येक सुझाए गए शब्द का परीक्षण किया है, लेकिन विशिष्ट आवश्यकताओं के आधार पर वास्तविक प्रदर्शन विचलित हो सकता है। यदि आपको कोई त्रुटि मिलती है, रचनात्मक विचार हैं, या अच्छे सुझाए गए शब्द हैं, तो कृपया प्रतिक्रिया प्रदान करने और योगदान करने के लिए स्वतंत्र महसूस करें [GitHub पृष्ठ](https://github.com/rockbenben/ChatGPT-Shortcut/discussions/11)।

यदि आप जानकारी को सारांशित या संघनित कर रहे हैं, तो आप मूल प्रतिक्रियाओं को और परिष्कृत करने के लिए जीपीटी का उपयोग कर सकते हैं, जिससे उत्तरों की सटीकता बढ़ जाती है। इसके अलावा, सुझाए गए शब्द न केवल उत्पादकता उद्देश्यों के लिए काम करते हैं, बल्कि आपकी सोच को व्यापक बनाने, रचनात्मकता को प्रोत्साहित करने, कई दृष्टिकोणों से समस्याओं पर विचार करने और उन मुद्दों को हल करने में भी मदद करते हैं जिन्हें सोच प्रक्रिया के दौरान आसानी से अनदेखा किया जाता है।