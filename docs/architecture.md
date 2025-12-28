# ACIP - AI Content Intelligence Platform - architecture

A pipeline rather than a prompt. Topic planning establishes the cluster, distinct article templates enforce different structures - authority piece, deep dive, specialist, comparison, case study - and a generation stage fills them. Because each template has its own shape, the output does not collapse into one repeated format.

## Components

### Topic planning

Cluster and authority mapping

### Template engine

Five structurally distinct article formats

### Generation pipeline

Staged content production

### Publishing output

HTML and PHP render targets

### CLI

Scriptable pipeline control

## Stack

| Layer | Technology |
| --- | --- |
| Language | JavaScript, Node.js |
| Generation | LLM content pipeline |
| Templates | HTML and PHP article formats |
| Interface | Command-line pipeline runner |

Designed and implemented by Muhammad Tanveer - Full-Stack AI Automation Engineer.