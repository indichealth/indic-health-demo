
## Annotation Guidelines
This document is a guide for annotating translation techniques in a parallel corpus from English queries to three target Indian languages: Hindi, Bengali and Telugu. The queries are translated from English to these three target languages using Bing Translator. Then the native speakers need to manually verify these translations, and correct the translations whenever required. Moreover, we also ask them to manually tag the different medical entities mentioned in the queries.
Instructions:
Fill up the column “Manually Written Question_in_Hindi_Script” using the following guidelines, also use https://www.google.com/inputtools/try/ for typing in your native language:
*      Make sure that all the words in the target language are transcribed in that particular target language. 
For example: in the sentence: “क्या Augmentin 625 Duo Tablet के प्रयोग से संबंधित कोई विशिष्ट सावधानियां हैं?”
We should replace “Augmentin 625 Duo Tablet” with “ऑगमेंटिन ६१५ डुओ टैबलेट”.
*      For each drug or disease, name if there is any existing vocabulary of drug/disease in that target language, then replace it with that name, otherwise keep the transliterated version of the same.
For example: in the sentence we keep the transliterated version of “Augmentin 625 Duo Tablet” in the target language :
“क्या Augmentin 625 Duo Tablet के प्रयोग से संबंधित कोई विशिष्ट सावधानियां हैं?”
We should replace “Augmentin 625 Duo Tablet” with “ऑगमेंटिन ६१५ डुओ टैबलेट”.
*      Correct the word by word translation to natural looking sentences.
For example: in the sentence “could taking valium result in a false positive on a pregnancy test?” has been machine-translated into “ভ্যালিয়াম গ্রহণ একটি গর্ভাবস্থার পরীক্ষায় একটি মিথ্যা ইতিবাচক ফলাফল গ্রহণ করতে পারে?”. This does not look very natural indeed.
* Write the corrected queries in its english transliterated form. 
For example: Hindi: ” क्या करें “
English transliterated form: “ kya kare “
*     Identify the different medical entities in the corresponding column in the sheet (Entities: disease, treatment, drug).
        Examples of entities:
a.       “<drug> ভ্যালিয়াম </drug> গ্রহণ একটি গর্ভাবস্থার পরীক্ষায় একটি মিথ্যা ইতিবাচক ফলাফল গ্রহণ করতে পারে?”.
b.   	“<disease> ফুসফুসের ক্যান্সার </disease> কি <disease> মস্তিষ্কে মেস্ট্যাসিস </disease> করে?

Add the entity name to their respective columns in the sheet. If there are multiple entities in the same row, separate them with commas.

*    Also, maintain a log of any challenges you face during the annotation process in a google doc and share the link with us. 
