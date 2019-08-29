---
layout: post
title:      "How to Access Hacker News APIs with Redux Dispatch and Redux-Thunk"
date:       2019-08-29 22:18:38 +0000
permalink:  how_to_access_hacker_news_apis_with_redux_dispatch_and_redux-thunk
---


Hacker News API making the public Hacker News data available in near real time, but the Hacker news Ask, Show and Job Stories APIs only return a list of story ids. For example, the following Top news API only return an array of story ids.

To access each individual story’s data object, you have to create a fetch request base on each story id. For example, a story with story id 8863: https://hacker-news.firebaseio.com/v0/item/8863.json?print=pretty

Read more, please go to <https://medium.com/@hanke.liu/how-to-access-hacker-news-apis-and-render-news-contents-by-using-react-redux-d8a58aba3371>
