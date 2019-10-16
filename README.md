# Lab-6

# java_practice
# COMP2112-Lab 6
## ES6+ features:
Template Literals. String Interpolation
## 1).map function: The map() strategy makes another exhibit with the consequences of calling a capacity for each cluster component. The map() technique calls the gave capacity once to every component in a cluster, all together. Note: map() doesn't execute the capacity for cluster components without qualities.

![image of how the .map function works](https://github.com/RvndrDosanjh/Lab-6/blob/master/Screenshot%20(44).png)

function render() {
  main.innerHTML = tweets.map(tweet => `
        <aside>
         <div>
            <img class="avatar" src="${tweet.avatar}">
         </div>
         <div class="formatted-tweet">
            <h6><a href="https://twitter.com/${tweet.username}">${tweet.name}</a> <span class="username">@${tweet.username}</span></h6>
            <p>${tweet.tweet}</p>
            <div class="imgGifPoll">
            </div>
            <div>
                <section>
                    <div id="reactions" class="btn-group mr-2">
                        <button
                            type="button"
                            class="btn btn-secondary mdi mdi-message-outline"
                            aria-label="reply"
                        ></button>
                        <button
                            type="button"
                            class="btn btn-secondary mdi mdi-twitter-retweet"
                            aria-label="retweet"
                        ></button>
                        <button
                            type="button"
                            class="btn btn-secondary mdi mdi-heart-outline"
                            aria-label="like"
                            style=""
                        ></button>
                        <button
                            type="button"
                            class="btn btn-secondary mdi mdi-upload"
                            aria-label="share"
                        ></button>
                    </div>
                </section>
            </div>
        </div>
        </aside>
          `).join('');
}

# [More details about .map functions!] https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map

