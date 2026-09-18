---
permalink: /job-market-tracker/
title: "JOE Tracker"
classes: wide
---

This page tracks cumulative postings in the American Economic Association's [Job Openings for Economists](https://www.aeaweb.org/joe/) listings, organized by academic year. These do not represent the full universe of econ jobs.

<div style="height: 720px; width: 100%;">
  <iframe
    title="Interactive cumulative JOE postings by market week"
    src="{{ '/assets/images/joe-tracker/job_postings_by_week.html' | relative_url }}"
    style="border: 0; height: 100%; width: 100%;"
    loading="lazy">
  </iframe>
</div>

[Open chart in a new tab]({{ '/assets/images/joe-tracker/job_postings_by_week.html' | relative_url }}).

<noscript>
  <img src="{{ '/assets/images/joe-tracker/job_postings_by_week.png' | relative_url }}" alt="Cumulative JOE postings by market week">
</noscript>

*Updated through September 18, 2026.* Market week 0 begins on August 1. The chart counts postings by their JOE `Date_Active` date.

### Credit

I have simply cloned the JOE Tracker from [Paul Goldsmith-Pinkham](https://github.com/paulgp/joe-tracker) and begun updating it for the 2026-27 job market season. The original tracker and design are his, and any errors in this version are mine.