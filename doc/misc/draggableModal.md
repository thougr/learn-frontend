# 项目结构

```mermaid
flowchart TB
   subgraph DraggableModal
     subgraph DraggableModalInner
      subgraph Modal
      end
     end
   end

   subgraph draggableModalReducer
   end

   subgraph DraggableModalProvider
     DraggableModalContext
   end
  DraggableModalProvider--useReducer-->draggableModalReducer
  DraggableModal--useContext-->DraggableModalContext

```
