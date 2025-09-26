아래 CSS를 index.html의 <style> 안에 덮어써 주세요:

.brand img{ height:44px }        /* 72px -> 44px (40% 축소) */
@media (max-width:900px){ .brand img{ height:34px } }  /* 56px -> 34px */
