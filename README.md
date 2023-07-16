# Newsweek Clone
This is your second assignment and you will be using Bootstrap to clone Newsweek.

## Layout summary
At a window size of 992px and above, which is md breakpoint of bootstrap, the main content layout stays the same. The main article column is on the left, and the headlines side bar is on the right. Therefore, you only need to use col-md-* classes for the main column and the side bar as the column definition will remain in effect at the md and lg breakpoints.

At a window size of 992px and below, the main content layout is the same for sm and xs breakpoints. Therefore, you only need to use col-xs-* classes for the main column and the side bar. Both should take up full 12 columns. They will continue to take up 12 columns at the sm breakpoint because the col-xs-* classes will stay in effect when there are no col-sm-* classes added.

The two smaller articles need to be nested inside the main column, so it is always under the main article. Nest a <div class="row"> inside the main column to create the nested structure for the two articles.

Each small article will take up full 12 columns at the xs breakpoint, use col-xs-12. They will then change to 6 columns at the sm breakpoint, so use col-sm-6. They will remain to take up 6 columns above the sm breakpoint, you don't need to add md, lg classes since their column layout don't change.

## Deployed Website
https://jterrill-newsletter-clone.netlify.app/
