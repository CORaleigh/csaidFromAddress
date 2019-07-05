utility to create a report called append.txt of csaids based on addresses in address.csv

install: npm i

usage: node csaidFromAddress.js

notes: address.csv file must contain a header called ADDRESS (all in uppercase). The Street names must be in title case like 123 Main St and cannot contain any single quotes or pound signs. I haven't tested other special characters, but they too may cause the node process to crash with no error.
