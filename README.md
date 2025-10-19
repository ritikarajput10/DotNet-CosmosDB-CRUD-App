# 🌐 C# CRUD Web App with Azure Cosmos DB

A backend API built in **.NET 6 (C#)** that performs CRUD operations on **Azure Cosmos DB** and can be hosted on **Azure App Service**.

## Features
- Create, Read, Update, Delete operations
- Cosmos DB integration with SDK
- Deployed to Azure App Service
- Scalable architecture using App Service Plan

## Tech Stack
- C#, .NET 6
- Azure Cosmos DB
- Azure App Service
- REST API

## Run Locally
1. Add your Cosmos DB connection string to `appsettings.json`.
2. Run:
```bash
dotnet restore
dotnet run --project DotNet-CosmosDB-CRUD-App
```
Visit: `http://localhost:5000/api/items`

## Deployment
1. Create Cosmos DB and App Service in Azure.
2. Update `appsettings.json` with your Cosmos DB connection string.
3. Deploy using Azure DevOps pipeline or Azure CLI.
