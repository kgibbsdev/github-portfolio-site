---
title: Home
layout: home
permalink: /
---

### Developer for Hire

Hello! My name is Kyle Gibbs, and I'd like to work with you!

Here's a quick summary about myself.

I'm a Backend and Tools developer with experience working for companies of any size or industry. I'm strongest in the .NET suite of technologies (C#, ASP.NET, SQL Server), but I also have experience with several other languages in a backend context like Python, C++, Go, and Javascript.

I'm a quick learner - picking up complex topics and proprietary tools quickly for a shorter ramp-up time.

I'm passionate about good technical docs. Is your documentation out of date, disorganized, or a pain point for your team? I have experience writing accessible technical documentation for humans of any tech knowledge level.


=============== Cool Stats ===============

{% assign start_year = "2022-12-01" | date: "%Y" | plus: 0 %}
{% assign start_month = "2022-12-01" | date: "%m" | plus: 0 %}
{% assign current_year = "now" | date: "%Y" | plus: 0 %}
{% assign current_month = "now" | date: "%m" | plus: 0 %}

{% assign year_diff = current_year | minus: start_year %}
{% assign month_diff = current_month | minus: start_month %}

{% if month_diff < 0 %}
    {% assign year_diff = year_diff | minus: 1 %}
    {% assign month_diff = month_diff | plus: 12 %}
{% endif %}

{% assign decimal_months = month_diff | divided_by: 12.0 %}
{% assign total_years = year_diff | plus: decimal_months %}

{% assign total_years_scaled = total_years | times: 10 %}
{% assign total_years_ceil = total_years_scaled | ceil %}
{% assign total_years_rounded_up = total_years_ceil | divided_by: 10.0 %}

Kyle has worked in the games industry for {{ total_years_rounded_up }} years 
{% assign start_year = "2019-12-01" | date: "%Y" | plus: 0 %}
{% assign start_month = "2019-04-01" | date: "%m" | plus: 0 %}
{% assign current_year = "now" | date: "%Y" | plus: 0 %}
{% assign current_month = "now" | date: "%m" | plus: 0 %}
{% assign year_diff = current_year | minus: start_year %}
{% assign month_diff = current_month | minus: start_month %}

{% if month_diff < 0 %}
    {% assign year_diff = year_diff | minus: 1 %}
    {% assign month_diff = month_diff | plus: 12 %}
{% endif %}

{% assign decimal_months = month_diff | divided_by: 12.0 %}
{% assign total_years = year_diff | plus: decimal_months %}
{% assign total_years_scaled = total_years | times: 10 %}
{% assign total_years_ceil = total_years_scaled | ceil %}
{% assign total_years_rounded_up = total_years_ceil | divided_by: 10.0 %}
and has been a software engineer for  {{ total_years_rounded_up }} years