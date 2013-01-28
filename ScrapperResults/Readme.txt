There are 2 files contained in this folder:
1. CrawledData20130128ExtractedLuke.xml - this is the result obtained from extracting the SolrIndex(Lucene) using luke, open source lucene index viewer.
2. CrawledData201301128ExtractedSolrFrontEnd.xml - this is the result obtained from extracting Solr frontend.
==========================================================================================================================================================================
How the crawled data is generated:

URL: http://www.malaysia.gov.my/

depth of search:35
topN, number of page to be retrieved at each depth : 35

PDF plugin is off

For CrawledData20130128ExtractedLuke.xml, you can see top term count. This is the top terms found in all pages being crawled.

The purpose of this demo is to show that lucene index can be extracted and used for the purpose of sinar project. Since luke is an open source lucene index viewer, we can reuse it to output a structure data in a form of xml, json or csv.

==========================================================================================================================================================================
Description in both of the files:

There are 3 items you need to lookout:
1. URL - the links of the scrapped page.
2. Title - the title of the scrapped page.
3. Content - the text which is scrapped.

Regardless of whatever the format of the page (PDF, word, tables) it will be extracted as text in "content" in lucene index.

==========================================================================================================================================================================

Let me know if you have any inquiries.