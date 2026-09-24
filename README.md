# handwritten-digit-recognition

Handwritten Digit Recognition هو مشروع لتصنيف الأرقام المكتوبة بخط اليد باستخدام Neural Networks (MLPClassifier) من مكتبة Scikit-learn. يعتمد المشروع على Digits Dataset، حيث يتم تجهيز البيانات وتقسيمها إلى Training وTesting Sets، ثم تطبيق StandardScaler على البيانات.

تم تدريب ومقارنة عدة نماذج MLP بتكوينات مختلفة للشبكات العصبية ودوال التنشيط مثل ReLU, Tanh, و Logistic، بدايةً من نموذج بسيط بطبقة مخفية واحدة وحتى نماذج أكثر تعقيدًا متعددة الطبقات.

في النهاية، يتم اختيار النموذج صاحب أعلى Accuracy، ثم تقييم أدائه باستخدام Classification Report و Confusion Matrix لتوضيح مدى دقة النموذج في التعرف على كل رقم.

التقنيات المستخدمة:

Python
NumPy
Matplotlib
Seaborn
Scikit-learn
MLPClassifier
Neural Networks
StandardScaler
Confusion Matrix

هدف المشروع: دراسة تأثير حجم وتعقيد الشبكة العصبية ودالة التنشيط على أداء نموذج التعرف على الأرقام المكتوبة بخط اليد.
