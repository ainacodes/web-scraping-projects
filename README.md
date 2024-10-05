# Web Scraping Projects

This repos contains some of the results of web scraping projects that I've done.
The actual results are in `csv` and `json` format.

My primary approach for web scraping is using the `available API` from the backend.
If there is no available API, I will use `Scrapy` then `beautifulSoup`, `selenium` or `playwright`.

<table>
    <tr>
        <th>Website</th>
        <th>Descriptions</th>
        <th>Results</th>
        <th>Repos</th>
    </tr>
    <tr>
        <td>
            <a href="https://www.tripadvisor.com/Restaurant_Review-g60763-d478965-Reviews-or45-Gallaghers_Steakhouse-New_York_City_New_York.html">Tripadvisor Restaurant</a>
        </td>
        <td>
            Collect the restaurant information along with individual customers reviews
        </td>
        <td>
            <a href="https://github.com/ainacodes/tripadvisor_scraper/blob/main/OUTPUT/tripadvisor_ny_restaurant_reviews_details_page_1_10.csv">tripadvisor_ny_restaurant_reviews.csv</a>
        </td>
        <td>
            <a href="https://github.com/ainacodes/tripadvisor_scraper">tripadvisor-scraper</a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://www.decathlon.com/collections/backpacks-bags">Shopify-based website - Decathlon US</a>
        </td>
        <td>
            Collect the product details using <strong>Scrapy</strong>
        </td>
        <td>
            <a href="https://github.com/ainacodes/decathlonUS_scraper/blob/main/products_details.csv">products_details.csv</a>
        </td>
        <td>
            <a href="https://github.com/ainacodes/decathlonUS_scraper">decathlonUS_scraper</a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://www.tradingview.com/screener/">
                TradingView - Stock Screener
            </a>
        </td>
        <td>
            Collect all the parameters.<br>
            Collect all the the parameters based on the filter needed.<br>
            Total data collected: 14,217
        </td>
        <td>
            <a href="https://github.com/ainacodes/TradingView-scraper/blob/main/stocks_data.csv">stocks_data.csv</a>
        </td>
        <td>
            <a href='https://github.com/ainacodes/TradingView-scraper'>TradingView-scraper</a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="">Youtube Scraper</a>
        </td>
        <td>
            Collect the "TITLE", "LINKS", "VIEWS", "DURATION", "DATE" and "CHANNEL_NAME" for the first 50 results that are appear in the search page. Taking the input from user in list search term in excel file.
        </td>
        <td>
            <a href="https://github.com/ainacodes/yt_scraper/blob/master/video_data.csv">video_data.csv</a>
        </td>
        <td>
            <a href="https://github.com/ainacodes/yt_scraper">youtube-scraper</a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="">Youtube Scraper API</a>
        </td>
        <td>
            Use <strong>Youtube Data API</strong> to retrive the data such as total views, total subscribers and total videos posted
        </td>
        <td>
            <a href="https://github.com/ainacodes/youtube_scraper_dataAPI/blob/main/result.png">result.png</a>
        </td>
        <td>
            <a href="https://github.com/ainacodes/youtube_scraper_dataAPI">youtube_scraper_dataAPI</a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://www.aliexpress.com/">Ali Express</a>
        </td>
        <td>
            Collect the data for "IMAGE", "TITLE", "PRICE" and "LINK" based on the user input product
        </td>
        <td>
            <a href=""></a>
        </td>
        <td>
            <a href="https://github.com/ainacodes/aliexpress_scraper">aliexpress_scraper</a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://www.tradingview.com/stock-screener/">
                TradingView - StockScreener 2.0
            </a>
        </td>
        <td>
            Collect all the parameters.<br>
            Collect all the the parameters based on the filter needed.<br>
            Total data collected: 14,468
        </td>
        <td>
            <a href="./results/tradingView_stockScreener2.0.png">TradingView-StockScreener2.0.png</a><br>
            <a href="./resultstrading_view_all_data.csv">trading_view_all_data.csv</a>
        </td>
        <td>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://www.ebay.com">Ebay</a>
        </td>
        <td>
            Download images that appears on search result page using Selenium.
        </td>
        <td>
             <a href="./results/ebay-img-scrape.png">ebay-img-scrape.png</a>
        </td>
        <td>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://www.etsy.com">Etsy</a>
        </td>
        <td>
            Collect 'product name', 'price', 'number of download for that product' and 'product URL' appears on search result page using Selenium.
            <br>
            <a href="./code_snippets/etsy_code.png">code snippets</a>
        </td>
        <td>
             <a href="./results/birthday_card_canva_template.csv">birthday_card_canva_template.csv</a>
        </td>
        <td>
        </td>
    </tr>
        <tr>
        <td>
            <a href="https://www.futurepedia.io/">futurepedia.io</a>
        </td>
        <td>
            Collect all AI Copywriting tools using Selenium.
        </td>
        <td>
             <a href="./results/copywriting_assistant.csv">copywriting_assistant.csv</a>
        </td>
        <td>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://www.ibba.org/find-a-business-broker/">IBBA</a>
        </td>
        <td>
            Collect all the data for SEARCH BY BROKER OR COMPANY NAME using API.<br>
            Total rows: 1049
        </td>
        <td>
             <a href="./results/ibba_lists.png">ibba_lists.png</a>
        </td>
        <td>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://semma.com.au/member-directory/">SEMMA member directory</a>
        </td>
        <td>
            Collect all the information from the member directory.<br>
            Total data collected: 208
        </td>
        <td>
            <a href="./results/semma_AU.png">semma_AU.png</a><br>
            <a href="./results/semma_data_cleaned.csv">semma_data_cleaned.csv</a>
        </td>
        <td>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://www.zocdoc.com/">Zocdoc</a>
        </td>
        <td>
            Collect all names under aetna plans using API.
        </td>
        <td>
             <a href="./results/aetna_plans.json">aetna_plans.json</a>
        </td>
        <td>
        </td>
    </tr>

</table>
