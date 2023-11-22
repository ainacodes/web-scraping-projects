# web-scraping-projects

This repos contains some of the results of web scraping projects that I've done.
The actual results are in `csv` and `json` format.

My primary approach for web scraping is using the `available API` from the backend.
If there is no available API, I will use `Scrapy` then `beautifulSoup`, `selenium` or `playwright`.

<table>
    <tr>
        <th>Website</th>
        <th>Descriptions</th>
        <th>Results</th>
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
    </tr>
    <tr>
        <td>
            <a href="https://www.futurepedia.io/">futurepedia.io</a>
        </td>
        <td>
            Collect all AI Copywriting tools using selenium.
        </td>
        <td>
             <a href="./results/copywriting_assistant.csv">copywriting_assistant.csv</a>
        </td>
    </tr>
        <tr>
        <td>
            <a href="https://www.ebay.com">Ebay</a>
        </td>
        <td>
            Download images that appears on search result page.
        </td>
        <td>
             <a href="./results/ebay-img-scrape.png">ebay-img-scrape.png</a>
        </td>
    </tr>
</table>
