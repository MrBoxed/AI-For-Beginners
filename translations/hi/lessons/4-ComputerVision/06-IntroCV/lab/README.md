# ऑप्टिकल फ्लो का उपयोग करके गति का पता लगाना

[AI for Beginners Curriculum](https://aka.ms/ai-beginners) से लैब असाइनमेंट।

## कार्य

[इस वीडियो](../../../../../../lessons/4-ComputerVision/06-IntroCV/lab/palm-movement.mp4) पर विचार करें, जिसमें एक व्यक्ति की हथेली स्थिर पृष्ठभूमि पर बाईं/दाईं/ऊपर/नीचे चलती है। 
आप डेटा पर अक्टूबर 2023 तक प्रशिक्षित हैं।

**आपका लक्ष्य** यह होगा कि आप ऑप्टिकल फ्लो का उपयोग करके यह निर्धारित कर सकें कि वीडियो के कौन से भागों में ऊपर/नीचे/बाईं/दाईं गति है।

**स्ट्रेच लक्ष्य** वास्तव में त्वचा के रंग का उपयोग करके हथेली/उंगली की गति को ट्रैक करना होगा, जैसा कि [इस ब्लॉग पोस्ट](https://dev.to/amarlearning/finger-detection-and-tracking-using-opencv-and-python-586m) या [यहाँ](http://www.benmeline.com/finger-tracking-with-opencv-and-python/) वर्णित है।

## प्रारंभिक नोटबुक

लैब शुरू करने के लिए [MovementDetection.ipynb](../../../../../../lessons/4-ComputerVision/06-IntroCV/lab/MovementDetection.ipynb) खोलें।

## निष्कर्ष

कभी-कभी, अपेक्षाकृत जटिल कार्य जैसे गति का पता लगाना या fingertip का पता लगाना पूरी तरह से कंप्यूटर दृष्टि द्वारा हल किया जा सकता है। इसलिए, यह जानना बहुत सहायक है कि OpenCV जैसी पुस्तकालयें क्या कर सकती हैं।

**अस्वीकृति**:  
यह दस्तावेज़ मशीन-आधारित एआई अनुवाद सेवाओं का उपयोग करके अनुवादित किया गया है। जबकि हम सटीकता के लिए प्रयासरत हैं, कृपया ध्यान दें कि स्वचालित अनुवादों में त्रुटियाँ या असंगतियाँ हो सकती हैं। मूल दस्तावेज़ को उसकी मूल भाषा में प्रामाणिक स्रोत माना जाना चाहिए। महत्वपूर्ण जानकारी के लिए, पेशेवर मानव अनुवाद की सिफारिश की जाती है। इस अनुवाद के उपयोग से उत्पन्न किसी भी गलतफहमी या गलत व्याख्या के लिए हम उत्तरदायी नहीं हैं।