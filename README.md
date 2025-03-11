# IAC Support Site 

This directory contains the support site information in the case of an emergancy and IAC resources are not available.

## Support URL
https://intersocietal-accreditation-commision.github.io/Support/

## Adding an article to the support feed Overview

Find the Single News Feed Item comment within the index.html file. Edit both the time element and the entry-body sections

Example: 
<!-- Single News Feed Item-->
                <article class="hentry entry archive-entry">
                  <span class="date">
                           
                      <time datetime="2025-01-15" class="entry-date">
                        <span class="month">Jan</span>
                        <span class="day">15</span><span class="comma">,</span>
                        <span class="year">2025</span>
                      </time>
               
                  </span>

                  <div class="entry-body">
                    <header class="entry-header">
                      <h2 class="h4 entry-title">
                       Site offline due to degraded service
                      </h2>
                    </header>

                    <div class="entry-summary">
                      <p>The IAC accreditation portal is not accessible. Please return to this page for any updates.</p>
                    </div>
                  </div>
                </article>
<!-- End Single News Feed Item-->

## Edit and Commit Process
To make changes, select the file from the repository and click the edit icon in the upper right corner.
To save changes, click Commit Changes to save the changes and commit them to the repository. 
All changes will start a build process.  

## Build process
The Github Pages functionality requires a build process. After a commit to Main it could take at most 2 minutes before updates are visible on the site.

