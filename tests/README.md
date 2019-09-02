| Mask | left_boundary | right_boundary | static_constraint | dynamic_constraint | Test Case                                                    |
| ---- | ------------- | -------------- | ----------------- | ------------------ | ------------------------------------------------------------ |
| X    |               |                |                   |                    | [test_masked_viterbi_decode](allennlp/conditional_random_field_test::TestConditionalRandomField#test_masked_viterbi_decode)<br />[test_viterbi_tags](tests.allennlp.conditional_random_field_test.TestConditionalRandomField#test_viterbi_tags)<br />[test_forward_works_with_mask](tests.allennlp.conditional_random_field_test.TestConditionalRandomField#test_forward_works_with_mask) |
|      |               |                | X                 |                    | [test_unmasked_constrained_viterbi_tags](tests.allennlp.conditional_random_field_test.TestConditionalRandomField#test_unmasked_constrained_viterbi_tags) |
| X    |               |                | X                 |                    | [test_constrained_viterbi_tags](tests.allennlp.conditional_random_field_test.TestConditionalRandomField#test_constrained_viterbi_tags) |
|      |               |                |                   |                    | [test_forward_works_without_mask](tests.allennlp.conditional_random_field_test.TestConditionalRandomField#test_forward_works_without_mask) |
|      |               |                |                   | X                  | [test_decode_without_mask](tests.test_dynamic_transition_constraint.TestDynamicTransitionConstraint#test_decode_without_mask) |
| X    |               |                |                   | X                  | [test_decode_with_mask](tests.test_dynamic_transition_constraint.TestDynamicTransitionConstraint#test_decode_with_mask) |
|      | X             | X              |                   |                    | [test_crf_add_boundary_energy_with_no_mask](tests.test_crf_add_boundary_energy.test_crf_add_boundary_energy_with_no_mask) |
| X    | X             | X              |                   |                    | [test_crf_add_boundary_energy_with_mask](tests.test_crf_add_boundary_energy.test_crf_add_boundary_energy_with_mask) |
