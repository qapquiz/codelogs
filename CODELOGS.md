# Codelog #4 - 2021-11-xx

-----

## Plan for the day

-----

## To investigate

-----

## Learned today

-----

## Done today

-----

## Resource list

-----

# Codelog #3 - 2021-11-05

-----

## Plan for the day
- [ ] fix: unnecessary sql condition in getSubscriptions
- [ ] feat: write some template for batch job for minting the tokens

-----

## To investigate
- find to way to check is this transaction already minted or not

-----

## Learned today
- cannot find the way to tracking minted yet
- if you want the monad to tracking all error step it should come with applicative

-----

## Done today
- [X] fix: unnecessary sql condition in getSubscriptions
- [X] feat: write some template for batch job for minting the tokens

-----

## Resource list
- [GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)
- [Prisma Pagination](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

-----

# Codelog #2 - 2021-07-13

-----

## Plan for the day
- [ ] compile contract with new implementation into Golang
- [ ] update server to match the parameters with new contract

-----

## To investigate
- must see the gas used inside the optimism of this new contract

-----

## Learned today
- there is hidden gas used in optimism because of Canonical Trasaction Chain + State Commitment Chain

-----

## Done today
- [X] compile contract with new implementation into Golang
- [X] update server to match the parameters with new contract

-----

## Plan for tomorrow

-----

## Resource list

-----

# Codelog #1 - 2021-07-12

-----

## Plan for the day
- [ ] add more field to the invoice table (e.g. items, date, due date)
- [ ] update interface of invoice PDF to look betetr


-----

## To investigate
- I do not know yet about the good design for invoice document. How should it look like? I have to find that first.
- Which data that is so important that make invoice invoice?

-----

## Learned today
I found out that there are so many invoice ui in this world. Just pick one with all neccessary information should be good enough.

-----

## Done today
- [X] add more field to the invoice table (e.g. items, date, due date)
- [X] update interface of invoice PDF to look betetr

-----

## Plan for tomorrow
I will work on updating the server to match with the Tar's contract version.

-----

## Resource list
