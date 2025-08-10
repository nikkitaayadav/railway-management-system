# Railway Management System — Case Study

This repository documents a full‑stack Railway Management System designed with a normalized relational schema, role‑based user flows, and admin analytics. The objective was to enable real‑time booking with dynamic seat availability, transparent pricing, and operational reporting for administrators.

## Project Overview

- Designed a fully normalized relational model with 13+ entities (Users, Bookings, Payments, Schedules, Routes, Trains, Tickets, Travel History, and more)
- Implemented role‑based features for passengers, staff, and admins, including search, booking, ride management, ticketing, and schedule editing
- Built complex SQL queries for real‑time seat availability, route‑specific schedules, passenger counts, and revenue/occupancy analytics
- Created admin dashboards for revenue tracking, demographic reports, and utilization trends
- I contributed primarily to **data modeling and SQL**, **admin analytics and reporting**, **role‑based feature design**, and **multi‑join query optimization**

This was a collaborative academic project; the original application code and deployment are linked below.

## Files Included

- `ERD.pdf`: Entity‑Relationship Diagram for the system.
- `businessRules.pdf` – Formal business rules and constraints.
- `report.pdf` – Design rationale, assumptions, and sample queries.
- `demoVideo.mp4` – Five‑minute walkthrough of the schema and flows.

## Architecture at a Glance

- **Data layer:** Normalized SQL schema with primary/foreign keys, constraints, and indexes for search and joins
- **Core flows:** Route search → Seat selection → Fare calculation → Booking and payment → Ticket issuance
- **Admin analytics:** Revenue by route and period, occupancy heatmaps, passenger demographics, and operational KPIs

## Selected SQL Highlights

- Real‑time **available seats** by schedule, class, and coach using joins over `Schedules`, `Trains`, `Tickets`, and `Bookings`
- **Revenue and occupancy** aggregation with window functions and grouping for admin dashboards
- **Passenger counts** and **route‑specific schedules** for operational planning and staffing

## My Role

I worked on the data model and analytics backbone:
- Designed the ERD and normalized schema
- Authored complex multi‑join queries for availability, revenue, and occupancy
- Shaped admin dashboards and role‑based feature behavior
- Supported frontend flows for searching, selecting seats, and confirming bookings

## Acknowledgments and Original Repository

- Original team repository: https://github.com/sydneyani/Tech-Solutions
- I thank my teammates for their collaboration across frontend, backend, and deployment

## Attribution
This work was completed as part of an academic project and is maintained at the original classroom repository: `sydneyani/Tech-Solutions`. This repository is a clean, self‑contained reconstruction.

