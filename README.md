# mix
rxjs 'から { bindCallback } を インポートします。   CONST  someFunction  =（、B、C）=> {    コンソール。ログ（a）; // 5 コンソール。ログ（b）; // 'string' コンソール。ログ（c）; // {someProperty： 'someValue'}       };   const  boundSomeFunction  =  bindCallback（someFunction）; boundSomeFunction（）。購読（値 => {    コンソール。ログ（値）// [5 '一部の文字列'、{someProperty 'someValueの'}] }）;  someFunction（5、' some string '、{someProperty ： ' someValue ' }）; // ->行がありません
