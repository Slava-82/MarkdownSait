# Привет World!!!
Этот сайт создан как шпаргалка для изучения и работы на языке разметки Markdown.  
## Что такое язык разметки Markdown?  
- Markdown - это простой и легковесный язык разметки, который используется для форматирования текста.
- Он был создан Джоном Грубером и Аароном Шварцем в 2004 году с целью облегчить написание и чтение текста в HTML-формате. 
- Markdown позволяет добавлять структуру и стиль к обычному тексту, используя простые символы и синтаксис.
- Markdown имеет простой и интуитивно понятный синтаксис, который легко изучить даже без предварительного опыта программирования.
- Он позволяет создавать заголовки, списки, ссылки, изображения, таблицы и другие элементы разметки. 
- Синтаксис Markdown состоит из комбинации обычного текста и специальных символов, таких как знаки решетки (#), звездочки (*) и дефисы (-).
  
  ## Приемущества:
  Markdown имеет несколько преимуществ, которые делают его популярным и полезным инструментом для создания и форматирования текста. Вот некоторые из основных преимуществ Markdown:

1. Простота использования: Markdown имеет простой и интуитивно понятный синтаксис, который легко изучить даже без предварительного опыта программирования. Он использует простые символы и структуру, что делает процесс написания и форматирования текста легким и быстрым.

2. Читаемость: Текст в формате Markdown легко читается как обычный текст. Вы не видите сложных тегов или структур, что делает его более понятным и приятным для чтения. Это особенно полезно при работе с длинными документами или веб-контентом.

3. Переносимость: Файлы Markdown могут быть открыты и прочитаны в любом текстовом редакторе. Они также могут быть легко преобразованы в другие форматы, такие как HTML, PDF или документы Microsoft Word. Это делает Markdown универсальным и удобным для работы с различными платформами и инструментами.

4. Поддерживается множеством платформ: Markdown широко поддерживается множеством платформ, включая веб-сайты, блоги, форумы, инструменты для разработки и многие другие. Многие платформы и приложения автоматически распознают и отображают Markdown-разметку, делая его удобным для использования в различных сценариях.

5. Возможность добавления элементов разметки: Markdown позволяет добавлять различные элементы разметки, такие как заголовки, списки, ссылки, изображения, таблицы и многое другое. Это дает вам большую гибкость и контроль над структурой и стилем вашего текста.

В целом, Markdown - это простой, гибкий и удобный язык разметки, который позволяет создавать читаемые и структурированные документы. Он идеально подходит для различных задач, от написания простого текста до создания сложных технических документов или веб-контента.


### [Параграф](2.md)
### [Заголовки](zagolovok.md)

#telegramSiteHelper_box {
		display: block;
    position: relative;
    width: 100%;
    background-color: #F7E8C4;
    border-radius: 4px;
    z-index: 9999;
    padding: 3px;
    box-sizing: border-box;	
}


#telegramSiteHelper_chatWrapper {
    display: block;
    position: relative;
    margin: 0px 0 3px 0;
    background-color: #FEFBF5;
    border-radius: 3px 3px 0 0;
    overflow-y: hidden;
    height: 261px;
}

#telegramSiteHelper_chatWrapper:hover{
    overflow-y: scroll;
}

#telegramSiteHelper_chatTextBox {
    display: block;
    position: relative;
    width: 100%;
    font-size: 10pt;
    border: 0px;
    box-sizing: border-box;
    padding: 10px;
    font-weight: normal;
    border-radius: 0 0 3px 3px;
}

#telegramSiteHelper_chatTextBox:focus{
background-color:#fff;
outline:none;
}


#telegramSiteHelper_chatInner{
width: 100%;
    box-sizing: border-box;
    height: auto;
    margin: 0;
    padding: 0;
    vertical-align: top;
    position: relative;
    top: 0;}
    
    
    #telegramSiteHelper_chatMessages{
    
    display: block;
    position: relative;
    margin: 0;
    padding: 0;
    list-style: none;
    
    }
    
   

#telegramSiteHelper_chatMessages li.msg{
    display: block;
    position:relative;
    margin: 5px;
    background-color: #fff;
    font-size: 9pt;
    padding: 7px 5px;
    -webkit-box-shadow: 0 1px 1px 1px #EEF0F5;
    box-shadow: 0 1px 1px 1px #EEF0F5;
		text-align:left;
}   
    
#telegramSiteHelper_chatMessages b.name{
font-weight:600;
display:inline-block;
width:56%;
text-align:left;
font-size:8pt;
}    

#telegramSiteHelper_chatMessages b.time{
font-weight:300;
display:inline-block;
text-align: right;
width: 40%;
color: #ccc;
font-size: 8pt;
}
    
    
#telegramSiteHelper_chatMessages .clr1{color:#1C3FA7}
#telegramSiteHelper_chatMessages .clr2{color:#EF4F4F}
 
 

#telegramSiteHelper_firstChatMsg {
    text-align: center;
    padding: 60px 10px;
    font-size: 20pt;
    color: rgba(0,0,0,0.4);
    letter-spacing: -0.5pt;
}