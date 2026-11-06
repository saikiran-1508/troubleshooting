# Project scope

Build a Windows desktop assistant that accepts spoken English commands and
performs a small set of local actions.

The existing local prototype uses Vosk for offline speech recognition,
SoundDevice for microphone input, Tkinter for the desktop interface, and
LangGraph to organize command interpretation, validation, execution and reporting.

Commands are matched against predefined phrases. No language model, external AI
API, RAG system, Firebase integration or phone interface is implemented yet.

This initial repository milestone publishes documentation and dependency
information. Application source remains local until subsequent uploads.
