TODO:

Backend:
* handle multiple attachments on a model, prefix column with attachment name
* create generator for migration
* create generator for intializer
* Normalize filenames

Frontend:
* Loader for filepicker js only if needed
* Eliminate need for jQuery
* make it a form builder function that can accept a different url name

Extra features:
* Work with DelayedJob
* Work with Sidekiq
* Fallback to filepicker url if paperclip url doesn't exist
* Filepicker converts to match paperclip styles
* FilePicker droppane support

