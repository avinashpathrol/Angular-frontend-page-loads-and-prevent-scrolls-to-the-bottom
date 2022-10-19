# Angular-frontend-page-loads-and-prevent-scrolls-to-the-bottom





Solution
Angular UI-Router recently updated it's app so that it automatically scrolls down to new views loaded by default. This was causing my app's pages to load scrolled down. To turn this off simply add the following attribute to your ui-view:

                                              <div ui-view="header" autoscroll="true"></div>
