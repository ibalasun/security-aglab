# Clean Up Your Environment

## Introduction

To clean up your environment after you are finished with this workshop, you need to terminate your target database. Terminating an Autonomous Database permanently deletes the instance from Oracle Cloud Infrastructure, removes all automatic backups, and deregesters the database from Oracle Data Safe. Oracle Data Safe automatically deprovisions resources when your free trial period expires. You cannot recover a terminated database.

Estimated Lab Time: 2 minutes

### Objectives

In this lab, you will:

- Terminate your target database

### Prerequisites

This lab assumes you have:

- Obtained an Oracle Cloud account and signed in to Oracle Cloud Infrastructure
- Finished doing the labs in this workshop

## Task 1: Terminate your target database

1. From Oracle Cloud Infrastructure's navigation menu, select **Oracle Database**, and then **Autonomous Transaction Processing**.

2. Under **List Scope** on the left, select your compartment.

3. Under **Filters**, select **Transaction Processing** for the workload type.

4. Click the name of your target database.

5. From the **More Actions** drop-down list, select **Terminate**.

6. On the **Terminate Autonomous Database** page, enter your database name to confirm that you want to terminate it.

7. Click **Terminate Autonomous Database**. 

