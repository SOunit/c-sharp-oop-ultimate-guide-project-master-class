# 37 access modifiers

- an assembly is a project

  - 1 solution has 2 projects, that means the solution has 2 assemblies

- private
  - only by class itself
- private protected
  - child only && inside same assembly
- protected
  - child only
  - other assembly can access too if child
- internal
  - in same assembly
- protected internal
  - in same assembly || child
  - only other class && other assembly CANNOT access
- public
  - all class can access
