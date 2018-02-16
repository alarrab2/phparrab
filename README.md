شرح تنصيب هيروكو على كوديني 
 -------------------
اولا نضع هذا الكود في ترمنل كوديني
1**
wget -O- https://toolbelt.heroku.com/install-ubuntu.sh | sh    انتر
  -------------------
ثانيا نربط كوديني مع هيروكو عبر الكود التالي
2**
heroku login   انتر\
نضع ايميل هيروكو 
وكلمة المرور الخاصة بالحساب
 --------------------
 3**
 تنصيب الملفات عبر الكود 
  git clone https://github.com/alarrab2/phparrab.git انتر
  
  cd phparrab  انتر
  
  ----------------
  من ثم نعطي المشروع اسم
  
heroku create اسم المشروع
-----------
نضيف المشروع 

git add . 

git commit -am "initial commit"
 
git push heroku master 

--------------------------
