# FLOW_as4
# SomeContract

This is the README file for the `SomeContract` smart contract.

## Table of Contents

- [Description](#description)
- [Struct](#struct)
- [Resource](#resource)
- [Functions](#functions)
- [Usage](#usage)

## Description

`SomeContract` is a smart contract written in Move language. It defines a contract with a struct and a resource. The struct, `SomeStruct`, contains four variables: `a`, `b`, `c`, and `d`. The resource, `SomeResource`, has a single variable `e`. The contract also provides various functions to interact with the struct and resource.

## Struct

The `SomeStruct` struct has the following variables:

- `a`: A publicly settable string variable.
- `b`: A publicly readable string variable.
- `c`: A string variable accessible only by the contract itself.
- `d`: A string variable accessible only by the struct itself.

## Resource

The `SomeResource` resource has the following variable:

- `e`: An integer variable.

## Functions

The `SomeContract` contract provides the following functions:

- `publicFunc()`: A publicly accessible function.
- `contractFunc()`: A function accessible only by the contract itself.
- `privateFunc()`: A function accessible only by the struct itself.
- `structFunc()`: A function to interact with the struct.

The `SomeResource` resource provides the following function:

- `resourceFunc()`: A function to interact with the resource.

The contract also has two special functions:

- `createSomeResource()`: Creates and returns a new instance of the `SomeResource` resource.
- `questsAreFun()`: A function for a specific purpose.

## Usage

To use the `SomeContract` contract, import it from the specified address (`0x01`). Then, you can interact with the contract and its functions.

### Area 1

In the `structFunc()` function, you can perform the following actions:

- **Write**: Modify the values of the variables `a`, `b`, `c`, and `d`.
- **Read**: Access the values of the variables `a`, `b`, `c`, and `d`.
- **Functions**: Call the functions `privateFunc()`, `publicFunc()`, and `contractFunc()`.

### Area 2

In the `resourceFunc()` function of `SomeResource`, you can perform the following actions:

- **Read**: Access the values of the variables `a`, `b`, and `c`.
- **Write**: Modify the value of the variable `a`.
- **Functions**: Call the functions `self.publicFunc()` and `self.contractFunc()`.

### Area 3

In the `questsAreFun()` function of `SomeContract`, you can perform the following actions:

- **Read**: Access the values of the variables `a`, `b`, and `c`.
- **Write**: Modify the value of the variable `a`.
- **Functions**: Call the functions `publicFunc()` and `contractFunc()`.

### Area 4

In the `main()` function, you can perform the following actions:

- **Read**: Access the values of the variables `a` and `b`.
- **Write**: Modify the value of the variable `a`.
- **Functions**: Call the function `publicFunc()`.

Please note that the specific actions mentioned in each area are subject to your implementation and requirements.
