# API Documentation for Blockchain Address Label Repository

This document provides detailed information about various APIs included in the `blockchain_address_label_repository`. Each entry includes a description of the API, its key endpoints, usage examples, and other relevant details.

---

## Arkham API Endpoint Description
- **Description**: Offers behavioural wallet labels based on the action this wallet has performed and proprietary labels for 11 Blockchains.
- **Size**: Dynamic, dependent on query parameters and filters.
- **Description**: Retrieves address labels from addresses
- **Format**: JSON
- **Language**: HTTP requests in any programming language, responses in English.
- **Supported Chains**: 11
- **Others**:
  - **Rate Limit**: 5 requests per second, with a burst allowance.
  - **Access Requirements**: Requires an API key provided manually upon request.
  - **Sample Call**:
    ```http
    GET https://api.arkhamintelligence.com/intelligence/address/{address}?chain=ethereum
    ```
  - **Sample Response**:
    ```json
     {
    "address": "0x...",
    "label": {
      "name": "Exchange",
      "type": "Custodial",
      "other_details": "..."
    },
      // Additional label details if applicable
    }
    ```
    
  - **Documentation**: Arkham API Access Documentation will be shared with API Key.
  - **Contact Information**: For API keys and support, fill this the form available in the [Arkham Intelligence Documentation](https://codex.arkhamintelligence.com/arkham-api).
  - **Note**: Labels can also be retrieved through their web app.


---

## Etherscan API Endpoint Description by Octart

- **Description**: This endpoint provides labels for Ethereum addresses, which may include classifications such as 'Exchange', 'Wallet', 'Contract', or indicators of illicit activities. For more possible labels please refer to [Etherscan](https://etherscan.io/labelcloud). 
- **Format**: JSON
- **Language**:  HTTP requests in any programming language, responses in English.
- **Supported Chains**: 1
- **Others**:
  - **Rate Limit**: Details any rate limits imposed on the endpoint (e.g., 5 requests per second).
  - **Access Requirements**: Open to anyone
  - **Sample Call**:
    ```http
    GET https://api.octalservice.com/etherscan-labels/addresses
    ```
  - **Sample Response**:
    ```json
    [
      {
        "address": "0x123abc...",
        "label": "Exchange Wallet",
        "category": "Exchange"
      },
      // More entries
    ]
    ```
  - **Documentation**: Please refer [Documentation](https://octal.art/etherscan-labels/) for more information.
  - **Contact Information**: N/A
  - **Note**: Labels can also be retrieved Etherscan.


---

## Nansen API Endpoint Description
- **Description**: Offers behavioural wallet labels based on the action this wallet has performed and proprietary labels for 20+ Blockchain.
- **Format**: JSON
- **Language**: HTTP requests in any programming language, responses in English.
- **Supported Chains**: 1
- **Others**:
  - **Rate Limit**: Based on subscription plan.
  - **Access Requirements**: Subscription required.
  - **Sample Call for Address Stats**:
    ```sql
    SELECT address, total_transactions, total_eth_received, first_active_date, last_active_date
    FROM address_stats
    WHERE address = 'specific_ethereum_address'
    ```
  - **Documentation**: Detailed at [Nansen Query Documentation](https://docs.nansen.ai/api/api-overview).
  - **Contact Information**: N/A
  - **Note**: Labels can also be retrieved through their web app.

