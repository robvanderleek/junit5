## CodeLimit Report

### Overview
| **Language** | **Files** | **Functions** | **Lines of Code** | **⚠** | **⛌** |
| --- | ---: | ---: | ---: | ---: | ---: |
| Java | 889 | 4768 | 25769 | 23 | 0 |
| JavaScript | 2 | 22 | 35 | 0 | 0 |
| **Totals** | **891** | **4790** | **25804** | **23** | **0** |

### Summary
| **Easy / Verbose** | **Hard-to-maintain ⚠** | **Unmaintainable ⛌** |
| ---: | ---: | ---: |
| 96% | 4% | 0% |

✅ 96% of the functions are maintainable, no refactoring necessary.

### Findings
| **Function** | **Length** | **File** |
| --- | ---: | --- |
| ⚠ [assertLinesMatchWithFastForward](https://github.com/robvanderleek/junit5/blob/HEAD/junit-jupiter-api/src/main/java/org/junit/jupiter/api/AssertLinesMatch.java#L115-L186) | 54 | junit-jupiter-api/src/main/java/org/junit/jupiter/api/AssertLinesMatch.java |
| ⚠ [resolve](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-engine/src/main/java/org/junit/platform/engine/support/discovery/EngineDiscoveryRequestResolution.java#L119-L166) | 48 | junit-platform-engine/src/main/java/org/junit/platform/engine/support/discovery/EngineDiscoveryRequestResolution.java |
| ⚠ [provideArguments](https://github.com/robvanderleek/junit5/blob/HEAD/junit-jupiter-params/src/main/java/org/junit/jupiter/params/provider/EmptyArgumentsProvider.java#L42-L93) | 48 | junit-jupiter-params/src/main/java/org/junit/jupiter/params/provider/EmptyArgumentsProvider.java |
| ⚠ [orderChildrenTestDescriptors](https://github.com/robvanderleek/junit5/blob/HEAD/junit-jupiter-engine/src/main/java/org/junit/jupiter/engine/discovery/AbstractOrderingVisitor.java#L60-L132) | 47 | junit-jupiter-engine/src/main/java/org/junit/jupiter/engine/discovery/AbstractOrderingVisitor.java |
| ⚠ [walk](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-engine/src/main/java/org/junit/platform/engine/support/hierarchical/NodeTreeWalker.java#L51-L100) | 46 | junit-platform-engine/src/main/java/org/junit/platform/engine/support/hierarchical/NodeTreeWalker.java |
| ⚠ [nullSafeToString](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-commons/src/main/java/org/junit/platform/commons/util/StringUtils.java#L160-L205) | 42 | junit-platform-commons/src/main/java/org/junit/platform/commons/util/StringUtils.java |
| ⚠ [isWideningConversion](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-commons/src/main/java/org/junit/platform/commons/util/ReflectionUtils.java#L497-L550) | 42 | junit-platform-commons/src/main/java/org/junit/platform/commons/util/ReflectionUtils.java |
| ⚠ [assertArrayElementsEqual](https://github.com/robvanderleek/junit5/blob/HEAD/junit-jupiter-api/src/main/java/org/junit/jupiter/api/AssertArrayEquals.java#L351-L392) | 41 | junit-jupiter-api/src/main/java/org/junit/jupiter/api/AssertArrayEquals.java |
| ⚠ [toStream](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-commons/src/main/java/org/junit/platform/commons/util/CollectionUtils.java#L189-L229) | 41 | junit-platform-commons/src/main/java/org/junit/platform/commons/util/CollectionUtils.java |
| ⚠ [addTestSource](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-reporting/src/main/java/org/junit/platform/reporting/open/xml/OpenTestReportGeneratingListener.java#L306-L346) | 41 | junit-platform-reporting/src/main/java/org/junit/platform/reporting/open/xml/OpenTestReportGeneratingListener.java |
| ⚠ [resolveParameter](https://github.com/robvanderleek/junit5/blob/HEAD/junit-jupiter-engine/src/main/java/org/junit/jupiter/engine/execution/ParameterResolutionUtils.java#L114-L167) | 41 | junit-jupiter-engine/src/main/java/org/junit/jupiter/engine/execution/ParameterResolutionUtils.java |
| ⚠ [findAnnotation](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-commons/src/main/java/org/junit/platform/commons/util/AnnotationUtils.java#L140-L190) | 37 | junit-platform-commons/src/main/java/org/junit/platform/commons/util/AnnotationUtils.java |
| ⚠ [executionFinished](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-launcher/src/main/java/org/junit/platform/launcher/listeners/SummaryGeneratingListener.java#L96-L136) | 36 | junit-platform-launcher/src/main/java/org/junit/platform/launcher/listeners/SummaryGeneratingListener.java |
| ⚠ [loadClasspathResource](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-launcher/src/main/java/org/junit/platform/launcher/core/LauncherConfigurationParameters.java#L270-L310) | 35 | junit-platform-launcher/src/main/java/org/junit/platform/launcher/core/LauncherConfigurationParameters.java |
| ⚠ [invokeTestInstanceFactory](https://github.com/robvanderleek/junit5/blob/HEAD/junit-jupiter-engine/src/main/java/org/junit/jupiter/engine/descriptor/ClassBasedTestDescriptor.java#L319-L363) | 35 | junit-jupiter-engine/src/main/java/org/junit/jupiter/engine/descriptor/ClassBasedTestDescriptor.java |
| ⚠ [createExecutions](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-testkit/src/main/java/org/junit/platform/testkit/engine/Executions.java#L253-L300) | 34 | junit-platform-testkit/src/main/java/org/junit/platform/testkit/engine/Executions.java |
| ⚠ [tryToLoadClass](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-commons/src/main/java/org/junit/platform/commons/util/ReflectionUtils.java#L851-L899) | 33 | junit-platform-commons/src/main/java/org/junit/platform/commons/util/ReflectionUtils.java |
| ⚠ [findRepeatableAnnotations](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-commons/src/main/java/org/junit/platform/commons/util/AnnotationUtils.java#L328-L369) | 32 | junit-platform-commons/src/main/java/org/junit/platform/commons/util/AnnotationUtils.java |
| ⚠ [addFilters](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-console/src/main/java/org/junit/platform/console/tasks/DiscoveryRequestCreator.java#L93-L133) | 32 | junit-platform-console/src/main/java/org/junit/platform/console/tasks/DiscoveryRequestCreator.java |
| ⚠ [fromQuery](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-engine/src/main/java/org/junit/platform/engine/support/descriptor/FilePosition.java#L80-L114) | 31 | junit-platform-engine/src/main/java/org/junit/platform/engine/support/descriptor/FilePosition.java |
| ⚠ [fromQuery](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-engine/src/main/java/org/junit/platform/engine/discovery/FilePosition.java#L85-L119) | 31 | junit-platform-engine/src/main/java/org/junit/platform/engine/discovery/FilePosition.java |
| ⚠ [convert](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-commons/src/main/java/org/junit/platform/commons/support/conversion/ConversionSupport.java#L102-L137) | 31 | junit-platform-commons/src/main/java/org/junit/platform/commons/support/conversion/ConversionSupport.java |
| ⚠ [printTo](https://github.com/robvanderleek/junit5/blob/HEAD/junit-platform-launcher/src/main/java/org/junit/platform/launcher/listeners/MutableTestExecutionSummary.java#L153-L191) | 31 | junit-platform-launcher/src/main/java/org/junit/platform/launcher/listeners/MutableTestExecutionSummary.java |

Generated by [CodeLimit](https://getcodelimit.github.io)
