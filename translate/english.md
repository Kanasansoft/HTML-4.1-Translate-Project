# HTML 4.1 has been recommended

HTML 4.1 has been recommended is a new version of HTML.
Was added in HTML 4.1 will become the only specification for April Fool's Day.
It might appear to strange from being up only this only in the specification additional version is, but I would like to explain, including the reason.


## History of the introduction

Every year, the April Fool's Day April 1 each site has become that it is customary to create a special page of April Fool's Day, elaborate ingenuity.
Many of the special page it is being deleted and April Fool is finished, but some of the content continues to remain on the Internet.
This trend is noticeable in April Fool's entry that has been published in particular the personal blog.
Within April 1 takes advantage of the net while warning Internet users, but at the time of the usual net use many users will solve the warning.
When visit to the content of the accident April Fool at a time like this, there is a risk of the information that has been written to swallow.
Also, be adapted to take is determined that the special page of April Fool's Day in appearance, many can not tell the judge to screen reader users, it is also a problem with the accessibility basis.
Such a page but each search engine so that it does not appear in the search results has continued to be improved, abnormal and raise the weasel pretend to search engine is the root of the elaborate special page to the extent that it can be said also, April Fool's content judgment I was led to the proposal of specifications for.
In order to be surprised to lie of information to ensure that no tumble from Blanco also, I think it was a wise decision.

Below, we use terms such as "lie information," "lie page", but it means "April Fool's lie information". When would write all, we have omitted so hard to read and Mai has become redundant Please note.


## Change

It is a change, but specified for the following elements and meta element has been added.

### aprilfool element

It is used when you want to specify a lie information.
Etc. to publish the April Fool's entry in the blog, I'm assuming when there is a lie information on some of the pages.

```html
<aprilfool>HTML4.1 has been released</aprilfool>
```

### specified by the meta element

The entire page is used when a lie information.
It is intended to be used in a special page or special site.

```html
<meta name="aprilfool" content="true">
```

## Other specifications that were not adopted

For links to lie entry and lie page in the development stage of the specification, but there was also plan to specify the "aprilfool" to the rel attribute of the link element, it was postponed until HTML41 to become too complicated.

```html
<link rel="aprilfool" href="[lie Info URL]">HTML4.1 has been released</link>
```

Also, although the specification was also been proposed to use a file called "aprilfool.txt" that you can specify all under the directory as a lie information, here has been reject.
About aprilfool.txt, I will introduce because there was talk a little interesting.
Initially, it is directly under the lie information directory it was a specification determined by whether or not there is a aprilfool.txt file, search engine that was implemented by preceding a lie information determination process, the root just below the chance that there corporate site it will recognize the had aprilfool.txt file, the entire site accident that ends up being determined to lie information I have occurred.
And I heard the jokes of ideas of April Fool was the memo file, but would be PV is drastically reduced by an erroneous judgment, it seems to have become a sorry situation in joke for the person in charge.
Therefore, in the aprilfool.txt, specifications contain a string called AprilFool-Key has been proposed. AprilFool-Key is something you have to encode the UUID in Base64.
It is the reason that finally it has been reject, but the first place discussion of whether the use case is how much some of which specify all under the directory as lie information is now beginning.
As was also the accident of erroneous determination, it is a very powerful specification that can even be specified the entire site as a lie information.
Far from April Fools, in the article article of lie you have outgoing daily, the site even at the site where the whole is claiming to be a fiction, things that no longer lie becomes a fact after occurs, of misinformation and apology, etc. in the site , has slipped to the fact of the article.
From the fact that aprilfool.txt is (originally because it is not in the first place of the April Fools article is beyond the scope of the specification, but ...) that will not be used can be predicted and even in such sites, a number of opinion that aprilfool.txt's unnecessary became.
"Some of the facts of the article is"`<meta name = "aprilfool" content = "false">`"the may be specified," but there was also the opinion that, it was not enough to overturn the flow of reject.


## Why HTML 4.1 is not a HTML5.1 later?

Initially, HTML.next for granted, had progressed specification developed in the context of the HTML5.1.
However, the following opinion was issued from the administrator of the site of a senior.
You are managing the site using the "old CMS, but only until the output of the HTML 4.01 does not support. If a specification for the April Fool becomes after HTML5.1, be open to the public lie article become difficult. "
Indeed, it is the most opinion.
For this reason, it was decided to in order to be able to correspond with the old CMS even a little modification, to develop the HTML 4.1 that you have added only a specification for the April Fool in HTML 4.01.
Thus, exceptionally HTML 4.1 even CMS that support has ended has begun been released several corresponding version. In addition, even in CMS development is completely stopped, HTML 4.1 has been published has a corresponding patches and plug-ins, policy change of versioning became a successful outcome.


## Browser behavior

When you open a page that lie information has been included in the browser, a warning will be displayed.
For the Japanese version of the browser, "This page is April Fool's Day page. "Or" on this page contains information of April Fool's Day. "And it is a warning.
You can either be part of the browser you want to hide the lie information in the configuration change, so we came out even plug-ins that have the same function, those who are worried or Why not try to introduce.
The browser that judgment ability of such children is used is more immature, non-display function of lie information might be required.


## Other major cases

Search engine side support is different.
The place where lie information to the default search results so as not to appear, where you can specify in the search option, there is also an interesting "Search for the only lie information" at search site with additional options.
In addition, from the fact that now lie information can be easily determined, Web services that can be viewed as collected together jokes of April Fool has emerged.
Movement to exploit this specification also came out.
A company, and aim that the apology for the scandal does not appear in the search results, case to use the aprilfool element to the apology has occurred.
April Fool content determination process search engine of time that began to introduce is because had just engine that does not display a lie information in the search results.
However, apology is collected in jokes collection site, discovered that you are using the aprilfool elements, we would be in flames.
Each search service is now imposes a penalty for such use, it seems to be that the lower the rank of the entire corporate site.


## Summary

I think you and know, but this entry itself is a lie information.
