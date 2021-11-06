[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# AJAX and API's: Study

Use [DuckDuckGo](https://duckduckgo.com/) or your preferred search engine along with the provided resources to research and answer the [questions below](#questions).

## Required Reading

- [What is Ajax and Where is it Used in Technology](https://www.seguetech.com/ajax-technology/)
- [Pros and Cons of Ajax](https://www.c-sharpcorner.com/blogs/what-is-ajax)
- [XMLHttpRequest vs Fetch](https://www.sitepoint.com/xmlhttprequest-vs-the-fetch-api-whats-best-for-ajax-in-2019/)
- [Fetch vs Axios](https://blog.logrocket.com/axios-or-fetch-api/)

Browser Compatibility References:

- XMLHttpRequest or XHR @ [MDN](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest)
- Fetch API @ [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- Axios @ [GitHub](https://github.com/axios/axios#browser-support)

## Optional Reading

- [Why is Ajax not enough?](https://www.smashingmagazine.com/2015/01/why-ajax-isnt-enough/)

## Questions

1. What is Ajax? What advantages and disadvantages does it brings?

   ```
   Ajax is based on the acronym for asynchronous JavaScript and XML and is the name for a technique. It allows for callbacks by XMLHttpRequest Objects in the client side JavaScript to exchange data requests to a server. 
   The benefits include the lack of need for refreshing the entire page making it fast to use and user friendly to set up. 
   The callbacks help reduce processing on the server and the asynchronous calls allow for some working in another part of the browser to avoid waiting for all data to arrive before the user makes another act.

   The cons include the difficulty for SEO tracking, it can be harder to debug and it relies that JavaScript is compatible to be able to work.
   ```

2. Explain the differences between XMLHttpRequest, Fetch and Axios.

   ```
   XMLHttpRequest as the oldest technique which requires callbacks to understand if the request has errored and if the data has been returned. 
   Fetch is a newer API way which is less code, it does not use callbacks but still allows for async functioning. It ensures consistency in the use of generic Headers, Requests and Response interfaces. Fetch does not support timeouts and is cookieless by default which means you need to implement ways to counter this. 
   Axios automatically stringifies the data unlike fetch. Both Axios and XMLHttpRequest have easier ways to set up a progress indicator when compared to fetch which doesnt have one and instead needs a workaround. 
   ```

3. Which of the three has the poorest browser support - XMLHttpRequest (XHR), Fetch and Axios?

   ```
  As a disadvantage, Fetch being newer than XMLHttpRequest means patchs may result in more instability in browser compatibility in future broswer updates. The Fetch API is less stable for Internet Explorer and versions pre-2017 of Chrome, Firefox and Safari. Axios has better backward compatibility than fetch().
   ```

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice
