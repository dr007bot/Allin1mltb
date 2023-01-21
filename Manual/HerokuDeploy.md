## Heroku Guide

- ဒီ repo template ကို use template ကနေ မိမိ own repo လုပ်ပါ။ fork လို့လဲရပါတယ်
- မိမိ fork repo > setting > secrets > actions > new repo secret ထိနှိပ်ပြီး 
- 1. CONFIG_FILE_URL ကိုname နေရာထား value တွင် gist.githubusercontent~~~~~confif.env နှင့်ဆုံးသော link ဖြည့်
- 2. HEROKU_APP_NAME ကို name နေရာထား value တွင် မိမိသုံးမည့် heroku app name ထား အခြားသူနှင့်တူသော name ထားမိပါက error တက်နိုင်လို့ မတူအောင်ထားပါ။ e.g., allinone1357924680 စသဖြင့်
- 3. HEROKU_EMAIL - မိမိ heroku acc login email ဖြည့်
- 4. HEROKU_API_KEY - [ဒီနေရာမှ API Key](https://dashboard.heroku.com/account) ညာဖက်ဘေးက Revel ကိုနှိပ်ပြီး အလယ်ကွက်ထဲက •••••• မှပြောင်းသွားသော code ကူးထည့်
- ဒါတွေပြီးရင် repo ရဲ့ action နေရာကိုနှိပ်
- ⭐Deploy to Heroku ကိုထပ်နှိပ်
- အပြာစာတန်းဘေးက Run Workflow ⬇ကိုနှိပ်
- Run Workflow အစိမ်းရောင်စာကိုနှိပ်
- ၂ မိနစ်လောက်စောင့်ပြီးရင် Heroku Deploy ပြီးပါပြီ
- heroku acc ဝင်ပြီး ခုဏ အသစ် app ဖွင့် Resource သွား Worker on ပြီးသုံးနိုင်ပါပြီ
- ✅ CONFIG_FILE_URL တွင်သုံးမည့် config.env ရဲံ base url နေရာတွင် heroku app link ထည့်ပါ။ ဥပမာ အထက်က app name အရဆိုလျှင် https://allinone1357924680.herokuapp.com ပါ
- ☺ Heroku Cc များ တိုင်ပင်ဆွေနွေးနိုင်ရန် drivetalk သို့လာခဲ့ပါ။
