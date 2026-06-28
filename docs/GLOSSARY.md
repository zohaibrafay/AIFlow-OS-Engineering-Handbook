# Glossary

## Workflow

A directed model of work composed of nodes, edges, configuration, state, and execution rules.

## Node

A unit of workflow behavior. A node may transform data, call an external system, evaluate a condition, invoke an AI model, wait for an event, or trigger another workflow.

## Edge

A connection between nodes that defines possible execution flow, data flow, or conditional routing.

## Execution

A specific run of a workflow with input data, runtime state, logs, outputs, errors, and timing information.

## Scheduler

A service or component responsible for deciding when workflow work should be started, retried, resumed, delayed, or cancelled.

## Worker

A runtime process that performs workflow tasks assigned by the execution engine or scheduler.

## AI Agent

A system component that uses model reasoning, tools, memory, and policy constraints to pursue a bounded task.

## LLM

A large language model used for natural-language understanding, generation, reasoning, transformation, classification, tool selection, or agent behavior.

## Prompt

Structured input to a model, including instructions, context, examples, tool definitions, constraints, and requested output format.

## Memory

Persisted context that can be retrieved or updated across AI interactions. Memory may be user-specific, workspace-specific, task-specific, or system-governed.

## MCP

Model Context Protocol, a protocol pattern for exposing tools, resources, and contextual capabilities to AI systems through controlled servers.

## Connector

A packaged integration with an external system, API, data source, or service.

## Plugin

An extension package that adds nodes, connectors, triggers, actions, UI components, or runtime capabilities.

## Integration

The operational relationship between AIFlow OS and an external product, service, protocol, database, file system, or API.

## Workspace

A collaborative environment where users create, configure, execute, and manage workflows and related resources.

## Organization

An administrative boundary that may contain users, workspaces, billing settings, policies, audit logs, and shared integrations.

## Tenant

An isolation boundary for customer data, configuration, execution state, credentials, and governance policies.

## Execution Engine

The platform subsystem responsible for interpreting workflow definitions and coordinating node execution, state transitions, retries, and outcomes.

## Vector Database

A storage system optimized for embedding vectors and similarity search, commonly used for retrieval and semantic memory.

## Knowledge Base

A curated collection of documents, records, embeddings, metadata, and retrieval policies used by humans or AI systems.

## Trigger

An event, schedule, webhook, manual action, or external signal that starts or resumes a workflow.

## Action

A node behavior that performs work, such as sending a request, transforming data, creating a record, or invoking a model.

## Credential

A secret or identity artifact used to authenticate with an internal or external system.

## Runbook

Operational documentation that explains how to diagnose, mitigate, or recover from a known system condition.

