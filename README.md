# mine
Skip to content Search or jump to…  Pull requests Issues Marketplace Explore   @srisindhu07  Learn Git and GitHub without any code! Using the Hello World guide, you’ll start a branch, write comments, and open a pull request.   samfun123 / KtaneTwitchPlays 5 2827  Code Issues 33 Pull requests 2 Wiki Security Insights KtaneTwitchPlays/.editorconfig @samfun123 samfun123 Disable prefer var and add missing indentation options 8f95ffa on Oct 15, 2018 86 lines (71 sloc)  3.15 KB    root = true  [*.cs] indent_style = tab end_of_line = crlf  # "This." and "Me." qualifiers dotnet_style_qualification_for_field = false:error dotnet_style_qualification_for_property = false:error dotnet_style_qualification_for_method = false:error dotnet_style_qualification_for_event = false:error  # Language keywords instead of framework type names for type references dotnet_style_predefined_type_for_locals_parameters_members = true:warning dotnet_style_predefined_type_for_member_access = true:suggestion dotnet_style_coalesce_expression = true:none dotnet_style_null_propagation = true:none  # Expression preferences dotnet_style_object_initializer = true:suggestion dotnet_style_collection_initializer = true:suggestion dotnet_style_prefer_conditional_expression_over_assignment = true:suggestion dotnet_style_prefer_conditional_expression_over_return = true:suggestion  # Prefer var # csharp_style_var_for_built_in_types = true:none # csharp_style_var_when_type_is_apparent = true:none # csharp_style_var_elsewhere = true:none  # Expression bodies csharp_style_expression_bodied_methods = true:suggestion csharp_style_expression_bodied_constructors = false:none csharp_style_expression_bodied_operators = true:suggestion csharp_style_expression_bodied_properties = true:suggestion csharp_style_expression_bodied_indexers = true:suggestion csharp_style_expression_bodied_accessors = true:suggestion  # Pattern matching csharp_style_pattern_matching_over_is_with_cast_check = true:suggestion csharp_style_pattern_matching_over_as_with_null_check = true:none  # Inlined variable declarations csharp_style_inlined_variable_declaration = true:error  # "Null" checking preferences csharp_style_throw_expression = true:none csharp_style_conditional_delegate_call = true:suggestion  # Code block preferences csharp_prefer_braces = false:suggestion  # Organize usings dotnet_sort_system_directives_first = true  # Newline options csharp_new_line_before_open_brace = all csharp_new_line_before_else = true csharp_new_line_before_else = true csharp_new_line_before_catch = true csharp_new_line_before_finally = true csharp_new_line_before_members_in_object_initializers = true csharp_new_line_before_members_in_anonymous_types = true csharp_new_line_between_query_expression_clauses = true  # Indentation options csharp_indent_block_contents = true csharp_indent_braces = false csharp_indent_case_contents = true csharp_indent_switch_labels = true csharp_indent_labels = no_change  # Spacing options csharp_space_after_cast = true csharp_space_after_keywords_in_control_flow_statements = true csharp_space_between_method_declaration_parameter_list_parentheses = false csharp_space_between_method_call_parameter_list_parentheses = false csharp_space_before_colon_in_inheritance_clause = true csharp_space_after_colon_in_inheritance_clause = true csharp_space_around_binary_operators = before_and_after csharp_space_between_method_declaration_empty_parameter_list_parentheses = false csharp_space_between_method_call_name_and_opening_parenthesis = false csharp_space_between_method_call_empty_parameter_list_parentheses = false  # Wrapping options csharp_preserve_single_line_blocks = true csharp_preserve_single_line_statements = true © 2020 GitHub, Inc. Terms Privacy Security Status Help Contact GitHub Pricing API Training Blog About
