# Cacti gexport Plugin AI Instructions

## Project Overview
This is a Cacti plugin providing graph and data export capabilities.

## Key Rules
- Use prepared statements for ALL queries with variables
- Use get_request_var() for ALL user input
- Use html_escape() for ALL output of DB values in HTML
- No PHP 8.0+ features - target PHP 7.4
- All unserialize() must use allowed_classes => false
