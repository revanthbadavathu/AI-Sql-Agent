# AI-Powered Natural Language SQL Agent

Convert natural language questions into executable SQL queries using **GenAI (OpenAI GPT-4o-mini)**, **LangChain**, **FastAPI**, and a **React frontend**.

![Tech](https://img.shields.io/badge/Backend-FastAPI-green?style=flat-square)
![Tech](https://img.shields.io/badge/Frontend-React-blue?style=flat-square)
![Tech](https://img.shields.io/badge/LLM-OpenAI-orange?style=flat-square)
![Tech](https://img.shields.io/badge/Orchestration-LangChain-purple?style=flat-square)
![Tech](https://img.shields.io/badge/Database-PostgreSQL-blue?style=flat-square)

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Prerequisites](#prerequisites)
- [Backend Setup](#backend-setup)
- [Frontend Setup](#frontend-setup)
- [API Endpoints](#api-endpoints)
- [Demo Flow](#demo-flow)
- [SQL Safety](#sql-safety)
- [Future Enhancements](#future-enhancements)

---

## Overview
This project is a **GenAI-powered AI SQL Agent** that enables users to connect to a PostgreSQL database and ask questions in plain English. The system:

- Reads the database schema
- Converts natural language questions into SQL
- Validates SQL to prevent destructive operations
- Executes queries safely and returns results

It demonstrates:

- AI Agents
- NL2SQL (Natural Language → SQL)
- REST APIs
- Full-stack development
- LangChain + OpenAI integration

---

## Features
- Connect to any PostgreSQL database dynamically
- Natural language to SQL query generation using LLM
- Schema extraction for accurate SQL generation
- Read-only SQL execution with safety validation
- React frontend for database setup and interactive query execution
- Display gen

