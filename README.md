# CS305-Portfolio

Artemis Financial is a consulting company that creates personalized financial plans for its customers. Their software requirements for their web application are mainly security-focused. They are driven by security mainly because their application houses a lot of sensitive information regarding their clients. Specifically, they have asked for a verification step to ensure secure communications.

One thing I did very well when it came to addressing their software vulnerabilities, was finding the most efficient way to deal with those vulnerabilities. Some were false positives, being packages that weren't explicitly used in the application and could be suppressed. Other suppressions were a result of no workarounds, meaning we would have to wait for changes from the developer that manages these packages. But others, there were other packages that could achieve the same functionalities, but lacked vulnerabilities, or some were outdated. Software security adds to the company's well-being because it gives them and their clients peace of mind.

One part of the vulnerability assessment that was challenging was the sheer length of the assessment. I found it difficult to navigate, but at the same time, I found the initial list of vulnerabilities to be helpful in scrolling to the vulnerabilities that I needed to address.

I increased the layers of security by adding a secure HTTPS certificate to ensure secure communications, even if it was self-signed. Also, managing security vulnerabilities in the packages we used was very helpful in securing the application from threats.

I made certain code changes to make the app functional and secure. For instance, adding input validation is a vital step to securing the application from threats like SQL injection and so on. I regularly ran vulnerability checks to ensure no new vulnerabilities were introduced from my refactoring.

One tool that I found exceptionally helpful in this process was Maven, allowing me to audit all of my packages much more efficiently than any package manager I've used.

I would show future employers how I was able to aptly comprehend the vulnerability assessment and how efficiently I was able to pick out vulnerabilities that were either inapplicable or fixable.
