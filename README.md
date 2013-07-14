codegrader
==========

Codegrader allows you to define a checklist of criteria to use when reviewing code, then score each criteria from 1 to 10.
Scoring is done from the commit view in Github, so you can quickly grade as you read.

As you grade commits, averages and per commit scores  are then made available at http://codegrader.co, for tracking
developer performance and sharing with your developers.

I use this to monitor code quality at [Streetwise Media](http://streetwise-media.com) on a daily basis, and by leaving
comments on all commits with adjusted scores, have seen significant improvements in the work being done on our 
development team.

To get started, drag <a href="javascript:(function(){var i=document.getElementById('codegrader-iframe')||document.createElement('iframe'),u=window.location.href.split('/');if(u[5]!=='commit'){alert('This only works on commit pages');return;};i.style.position='fixed';i.style.top='0px';i.style.right='10px';i.style.width='200px';i.style.height='800px';i.id='codegrader-iframe';i.src='http://codegrader.co/grade/'+u[3]+'/'+u[4]+'/'+u[6];if(!document.getElementById('codegrader-iframe'))document.body.appendChild(i);}());">
this bookmarklet</a> to your toolbar, open a github commit page, and click.

Once you've graded one commit, you can access your dashboard at http://codegrader.co to view all your generated
scorecards.

You can also browse commits by repository via codegrader.co- the commit listing will include commits from all branches
on a specific repository in reverse chronological order, going back the last two weeks.

Any questions comments or concerns can be added as issues to this repository.
