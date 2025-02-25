[View code on GitHub](https://dune.com/docs/data-tables/spellbook/top tables/labels.md)

# Labels

The Labels technical guide is a feature on Dune that allows users to add, update, and query labels for any address. The guide explains what labels are, how to add them, and how to use them. 

A label is a piece of metadata about an address, a tag, or metadata. It comes in the form of a key-value pair. The key is the label type, and the value is the label name. Users can browse addresses and labels on the labels page. Labels on Dune are open-ended and crowd-sourced, meaning users are free to come up with new types and label names. 

The guide provides examples of what users can do with labels, such as labeling all addresses that used a certain dapp, labeling all addresses that hold a certain amount of a token, labeling all addresses that use a dapp more than X times per month, and labeling all addresses that sent money to Binance. Users can also do more novel and involved things around user patterns like who did arbitrage trades or profited from flash loans and so much more.

The Labels table stores labels in the new `labels.labels` table, which has the following schema: `id`, `address`, `name`, `blockchain`, `author`, `source`, `updated_at`, `label_type`, and `model_name`. 

The guide also provides a warning that the Using Labels section is currently under construction. 

Overall, the Labels technical guide provides a comprehensive overview of the Labels feature on Dune, including what labels are, how to add them, and how to use them. It also provides examples of what users can do with labels and explains how labels are stored in the Labels table.
## Questions: 
 1. What is the purpose of the Labels feature on Dune?
- The Labels feature on Dune allows users to add, update, and query labels for any address, providing metadata about an address in the form of a key-value pair.

2. How are labels created on Dune?
- Labels on Dune are open-ended and crowd-sourced, meaning users are free to come up with both new types and label names. Labels can be added using Dune queries, which can be used to label addresses based on various criteria such as dapp usage, token holdings, and more.

3. What is the schema of the `labels.labels` table?
- The `labels.labels` table stores labels and has columns for the label ID, address, name, blockchain, author, source, updated_at, label_type, and model_name.