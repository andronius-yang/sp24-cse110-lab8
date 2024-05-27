# Lab8-Starter

## How are graceful degradation and service workers related?

In essence, we can treat "fast internet access" as a "max technology" attribute because we cannot assume that all of our users have access to it. Therefore, we run into issues when networking isn't present and our content fails to load. Service workers serve as a "patch" to this issue because it allows information that requires internet connection to be store and cached, enabling them to be accessible offline. This preserves the functionality of our solution under conditions where "max technology" is not available, thereby fulfilling the goal of graceful degradation.

## PWA screenshot

![Screenshot of Progressive Web App](pwa.png)