# MedMatch

Upload a prescription, and MedMatch finds the nearest pharmacy that has all your medicines in stock.

## About

MedMatch is a web app that helps patients find where to fill their prescription without visiting pharmacy after pharmacy. Upload a photo of your prescription, and the app reads it with OCR and extracts the medicine names. You review and correct the detected list, and MedMatch checks it against pharmacy inventory. It then shows nearby pharmacies on a map, ranked by how many of your medicines they have in stock and how close they are.

## Features

- Prescription OCR with a review-and-edit step
- Pharmacies ranked by availability and distance
- Generic substitutes with price comparison when a brand is out of stock
- Split orders across two nearby pharmacies if none has everything
- Pharmacy dashboard to update stock (manual or CSV upload)
- Privacy-first: prescription images are not stored

## Problem It Solves

People often visit several pharmacies to find all their medicines, which wastes time and can lead to missed doses. MedMatch turns that search into one upload and one ranked list.

## Tech Stack

- Frontend: React, Leaflet
- Backend: Node.js, Express
- Database: MySQL
- OCR: Tesseract.js
