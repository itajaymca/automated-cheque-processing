# Automate Cheque Processing

## Problem Statement

    Bank handles large volumes of cheques in the clearing process. The process involves many technical verifications including signature verification. Some of these steps are manual and require human intervention to complete the process. The current process requires the high human capital deployment and longer processing time.

## Proposed Solution

    Verifying a customer's signatures with a predefined template,  requires three steps to follow. First, A customers  provides his details for verifying the valid Account in the bank. Second, The auto filled template will display along with a rectangle to sign the cheque, and The last step customer will click on the rectangle box to sign the cheque (Image shown). Template based processes are capable of handling all challenges that are there in the problem statement.

    Step 1
    ```
    Customer provide his/her details to verify account in the bank
    ```

    Step 2
    ```
    Pre populated customer details on the cheque with click here to sign the box
    ```

    Step 3
    ```
    Customer will click on the box to sign the cheque
    ```

# Structure

```
automated-cheque-processing/
├── packages/           # Yarn workspaces packages root
└── Makefile            # One Makefile to rule them all
```

# Requirements

- `make`
- `docker`
- `docker-compose`
- `microsoft azure`
- `microsoft visual studio code`
- `adobe`
- `tls cert`
