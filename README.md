# Kafka .NET Getting Started

This repository contains two projects: `Producer` and `Consumer`, both of which demonstrate how to use Kafka with .NET.

## Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Kafka](https://kafka.apache.org/quickstart)

## Getting Started

### Producer

The `Producer` project sends messages to a Kafka topic.

1. Navigate to the `Producer` directory:
    ```sh
    cd Producer
    ```

2. Restore the dependencies:
    ```sh
    dotnet restore
    ```

3. Run the producer:
    ```sh
    dotnet run
    ```

### Consumer

The `Consumer` project reads messages from a Kafka topic.

1. Navigate to the `Consumer` directory:
    ```sh
    cd Consumer
    ```

2. Restore the dependencies:
    ```sh
    dotnet restore
    ```

3. Run the consumer:
    ```sh
    dotnet run
    ```

## Configuration

Both projects use the `Confluent.Kafka` library to interact with Kafka. You can configure the Kafka settings in the respective `Program.cs` files.

## License

This project is licensed under the MIT License.
