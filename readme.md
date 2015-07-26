# Displays a customers bill

## Overview

## Acceptance behaviour

**In order to** check my bill
**As a** Customer
**I want to** see all information about my bill

**Scenario 1**: View my overall bill amount
**Given** They are an existing customer
**When** They view their bill
**Then** The total bill amount is displayed

**Scenario 2**: View their rented films
**Given** They are an existing customer
**When** They view their bill
**And** They want to see their rented films
**Then** All films rented over the last month are displayed
