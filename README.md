# temp
temp
javascript:{var currentPage = document.HkmcMainFrame.currentPage; var pages=document.HkmcMainFrame.pages; document.HkmcMainFrame.NextPage = function(){var page;var nextPageNum = currentPage + 1;if(pages[nextPageNum-1]){page = pages[nextPageNum-1]; currentPage = page.pg; document.HkmcMainFrame.MovePage(page.url);}else{page = "undefined";}};}
