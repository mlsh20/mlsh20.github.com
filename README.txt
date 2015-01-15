IKDD_HW10 使用D3製作圖表與圖表動畫

圖表使用之dataset，是<台灣政府資料開放平台>下載的<國際原油價格>
這個作業裡依照此資料做了兩種表格，一種是Multi-Series Line Chart，另一則為Difference Chart。
圖表之X軸皆為時間，以2014年的月份作為刻度。
圖表之Y軸皆為原油價格，以美金作為刻度。

引用之gallery為 http://bl.ocks.org/mbostock/3884955 與 http://bl.ocks.org/mbostock/3894205

transition的部分，使用了duration(),attr("transform", "translate(480,480)scale(23)rotate(180)"),.style("fill","red"),style("opacity",0.5)等，
使圖表產生外展，透明度，顏色的變化與可設定變化之時間長短。

製作出圖表後發現，從2014年開始，國際原油的價格呈現下降的趨勢。