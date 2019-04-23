# PMD Rules

The purpose of this document is to support resolving [#110](https://github.com/jensgerdes/sonar-pmd/issues/110).
For that purpose, we track the current rule status:
* Is the description up to date?
* Is the rule deprecated - meaning is there a built-in rule that replaces the PMD rule?
* If so, what is the alternative?

The PMD rules are divided into two sub categories:
* PMD Rules
* PMD Unit Test Rules

## PMD Rules

Rule name | Deprecated? | Alternative | Description up-to-date | Checked on
----------|-------------|-------------|------------------------|-----------
[AbstractClassWithoutAbstractMethod](./rules/AbstractClassWithoutAbstractMethod.md) | :ballot_box_with_check: | [S1694](https://rules.sonarsource.com/java/RSPEC-1694) | :white_check_mark: | 2019-04-23
[AbstractClassWithoutAnyMethod](./rules/AbstractClassWithoutAnyMethod.md) | :ballot_box_with_check: | [S1694](https://rules.sonarsource.com/java/RSPEC-1694) | :white_check_mark: | 2019-04-23
[AbstractNaming](./rules/AbstractNaming.md) | :ballot_box_with_check: | [S00118](https://rules.sonarsource.com/java/RSPEC-118) | :white_check_mark: | 2019-04-23
[AccessorClassGeneration](./rules/AccessorClassGeneration.md) | :x: | :heavy_minus_sign: | :white_check_mark: | 2019-04-23
[AddEmptyString](./rules/AddEmptyString.md) | :x: | :heavy_minus_sign: | :white_check_mark: | 2019-04-23
[AppendCharacterWithChar](./rules/AppendCharacterWithChar.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ArrayIsStoredDirectly](./rules/ArrayIsStoredDirectly.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AssignmentInOperand](./rules/AssignmentInOperand.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AssignmentToNonFinalStatic](./rules/AssignmentToNonFinalStatic.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AtLeastOneConstructor](./rules/AtLeastOneConstructor.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidAccessibilityAlteration](./rules/AvoidAccessibilityAlteration.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidArrayLoops](./rules/AvoidArrayLoops.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidAssertAsIdentifier](./rules/AvoidAssertAsIdentifier.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidBranchingStatementAsLastInLoop](./rules/AvoidBranchingStatementAsLastInLoop.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidCallingFinalize](./rules/AvoidCallingFinalize.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidCatchingGenericException](./rules/AvoidCatchingGenericException.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidCatchingNPE](./rules/AvoidCatchingNPE.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidCatchingThrowable](./rules/AvoidCatchingThrowable.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidConstantsInterface](./rules/AvoidConstantsInterface.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidDecimalLiteralsInBigDecimalConstructor](./rules/AvoidDecimalLiteralsInBigDecimalConstructor.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidDeeplyNestedIfStmts](./rules/AvoidDeeplyNestedIfStmts.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidDollarSigns](./rules/AvoidDollarSigns.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidDuplicateLiterals](./rules/AvoidDuplicateLiterals.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidEnumAsIdentifier](./rules/AvoidEnumAsIdentifier.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidFieldNameMatchingMethodName](./rules/AvoidFieldNameMatchingMethodName.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidFieldNameMatchingTypeName](./rules/AvoidFieldNameMatchingTypeName.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidFinalLocalVariable](./rules/AvoidFinalLocalVariable.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidInstanceofChecksInCatchClause](./rules/AvoidInstanceofChecksInCatchClause.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidInstantiatingObjectsInLoops](./rules/AvoidInstantiatingObjectsInLoops.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidLiteralsInIfCondition](./rules/AvoidLiteralsInIfCondition.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidLosingExceptionInformation](./rules/AvoidLosingExceptionInformation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidMultipleUnaryOperators](./rules/AvoidMultipleUnaryOperators.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidPrefixingMethodParameters](./rules/AvoidPrefixingMethodParameters.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidPrintStackTrace](./rules/AvoidPrintStackTrace.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidProtectedFieldInFinalClass](./rules/AvoidProtectedFieldInFinalClass.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidProtectedMethodInFinalClassNotExtending](./rules/AvoidProtectedMethodInFinalClassNotExtending.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidReassigningParameters](./rules/AvoidReassigningParameters.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidRethrowingException](./rules/AvoidRethrowingException.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidStringBufferField](./rules/AvoidStringBufferField.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidSynchronizedAtMethodLevel](./rules/AvoidSynchronizedAtMethodLevel.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidThreadGroup](./rules/AvoidThreadGroup.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidThrowingNewInstanceOfSameException](./rules/AvoidThrowingNewInstanceOfSameException.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidThrowingNullPointerException](./rules/AvoidThrowingNullPointerException.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidThrowingRawExceptionTypes](./rules/AvoidThrowingRawExceptionTypes.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidUsingHardCodedIP](./rules/AvoidUsingHardCodedIP.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidUsingNativeCode](./rules/AvoidUsingNativeCode.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidUsingOctalValues](./rules/AvoidUsingOctalValues.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidUsingShortType](./rules/AvoidUsingShortType.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[AvoidUsingVolatile](./rules/AvoidUsingVolatile.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[BadComparison](./rules/BadComparison.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[BeanMembersShouldSerialize](./rules/BeanMembersShouldSerialize.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
Big[IntegerInstantiation](./rules/IntegerInstantiation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[BooleanGetMethodName](./rules/BooleanGetMethodName.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[BooleanInstantiation](./rules/BooleanInstantiation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[BrokenNullCheck](./rules/BrokenNullCheck.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ByteInstantiation](./rules/ByteInstantiation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CallSuperFirst](./rules/CallSuperFirst.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CallSuperInConstructor](./rules/CallSuperInConstructor.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CallSuperLast](./rules/CallSuperLast.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CheckResultSet](./rules/CheckResultSet.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CheckSkipResult](./rules/CheckSkipResult.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ClassCastExceptionWithToArray](./rules/ClassCastExceptionWithToArray.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ClassNamingConventions](./rules/ClassNamingConventions.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ClassWithOnlyPrivateConstructorsShouldBeFinal](./rules/ClassWithOnlyPrivateConstructorsShouldBeFinal.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CloneMethodMustBePublic](./rules/CloneMethodMustBePublic.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CloneMethodMustImplementCloneable](./rules/CloneMethodMustImplementCloneable.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CloneMethodMustImplementCloneableWithTypeResolution](./rules/CloneMethodMustImplementCloneableWithTypeResolution.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CloneMethodReturnTypeMustMatchClassName](./rules/CloneMethodReturnTypeMustMatchClassName.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CloneThrowsCloneNotSupportedException](./rules/CloneThrowsCloneNotSupportedException.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CloseResource](./rules/CloseResource.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CollapsibleIfStatements](./rules/CollapsibleIfStatements.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CommentContent](./rules/CommentContent.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CommentDefaultAccessModifier](./rules/CommentDefaultAccessModifier.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CommentRequired](./rules/CommentRequired.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CommentSize](./rules/CommentSize.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CompareObjectsWithEquals](./rules/CompareObjectsWithEquals.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ConfusingTernary](./rules/ConfusingTernary.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ConsecutiveAppendsShouldReuse](./rules/ConsecutiveAppendsShouldReuse.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ConsecutiveLiteralAppends](./rules/ConsecutiveLiteralAppends.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ConstructorCallsOverridableMethod](./rules/ConstructorCallsOverridableMethod.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CouplingBetweenObjects](./rules/CouplingBetweenObjects.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[CyclomaticComplexity](./rules/CyclomaticComplexity.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DataflowAnomalyAnalysis](./rules/DataflowAnomalyAnalysis.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DefaultLabelNotLastInSwitchStmt](./rules/DefaultLabelNotLastInSwitchStmt.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DefaultPackage](./rules/DefaultPackage.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DoNotCallGarbageCollectionExplicitly](./rules/DoNotCallGarbageCollectionExplicitly.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DoNotCallSystemExit](./rules/DoNotCallSystemExit.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DoNotExtendJavaLangError](./rules/DoNotExtendJavaLangError.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DoNotHardCodeSDCard](./rules/DoNotHardCodeSDCard.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DoNotThrowExceptionInFinally](./rules/DoNotThrowExceptionInFinally.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DoNotUseThreads](./rules/DoNotUseThreads.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DontCallThreadRun](./rules/DontCallThreadRun.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DontImportJavaLang](./rules/DontImportJavaLang.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DontImportSun](./rules/DontImportSun.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DontUseFloatTypeForLoopIndices](./rules/DontUseFloatTypeForLoopIndices.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DoubleCheckedLocking](./rules/DoubleCheckedLocking.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[DuplicateImports](./rules/DuplicateImports.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptyCatchBlock](./rules/EmptyCatchBlock.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptyFinalizer](./rules/EmptyFinalizer.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptyFinallyBlock](./rules/EmptyFinallyBlock.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptyIfStmt](./rules/EmptyIfStmt.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptyInitializer](./rules/EmptyInitializer.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptyMethodInAbstractClassShouldBeAbstract](./rules/EmptyMethodInAbstractClassShouldBeAbstract.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptyStatementBlock](./rules/EmptyStatementBlock.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptyStatementNotInLoop](./rules/EmptyStatementNotInLoop.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptyStaticInitializer](./rules/EmptyStaticInitializer.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptySwitchStatements](./rules/EmptySwitchStatements.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptySynchronizedBlock](./rules/EmptySynchronizedBlock.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptyTryBlock](./rules/EmptyTryBlock.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EmptyWhileStmt](./rules/EmptyWhileStmt.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[EqualsNull](./rules/EqualsNull.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ExceptionAsFlowControl](./rules/ExceptionAsFlowControl.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ExcessiveClassLength](./rules/ExcessiveClassLength.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ExcessiveImports](./rules/ExcessiveImports.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ExcessiveMethodLength](./rules/ExcessiveMethodLength.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ExcessiveParameterList](./rules/ExcessiveParameterList.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ExcessivePublicCount](./rules/ExcessivePublicCount.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ExtendsObject](./rules/ExtendsObject.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[FieldDeclarationsShouldBeAtStartOfClass](./rules/FieldDeclarationsShouldBeAtStartOfClass.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[FinalFieldCouldBeStatic](./rules/FinalFieldCouldBeStatic.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[FinalizeDoesNotCallSuperFinalize](./rules/FinalizeDoesNotCallSuperFinalize.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[FinalizeOnlyCallsSuperFinalize](./rules/FinalizeOnlyCallsSuperFinalize.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[FinalizeOverloaded](./rules/FinalizeOverloaded.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[FinalizeShouldBeProtected](./rules/FinalizeShouldBeProtected.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ForLoopShouldBeWhileLoop](./rules/ForLoopShouldBeWhileLoop.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ForLoopsMustUseBraces](./rules/ForLoopsMustUseBraces.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[GenericsNaming](./rules/GenericsNaming.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[GodClass](./rules/GodClass.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[GuardDebugLogging](./rules/GuardDebugLogging.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[GuardLogStatement](./rules/GuardLogStatement.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[GuardLogStatementJavaUtil](./rules/GuardLogStatementJavaUtil.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[IdempotentOperations](./rules/IdempotentOperations.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[IfElseStmtsMustUseBraces](./rules/IfElseStmtsMustUseBraces.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[IfStmtsMustUseBraces](./rules/IfStmtsMustUseBraces.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ImmutableField](./rules/ImmutableField.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ImportFromSamePackage](./rules/ImportFromSamePackage.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[InefficientEmptyStringCheck](./rules/InefficientEmptyStringCheck.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[InefficientStringBuffering](./rules/InefficientStringBuffering.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[InstantiationToGetClass](./rules/InstantiationToGetClass.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[InsufficientStringBufferDeclaration](./rules/InsufficientStringBufferDeclaration.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
IntegerInstantiation | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[JumbledIncrementer](./rules/JumbledIncrementer.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[LawOfDemeter](./rules/LawOfDemeter.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[LocalHomeNamingConvention](./rules/LocalHomeNamingConvention.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[LocalInterfaceSessionNamingConvention](./rules/LocalInterfaceSessionNamingConvention.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[LocalVariableCouldBeFinal](./rules/LocalVariableCouldBeFinal.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[LoggerIsNotStaticFinal](./rules/LoggerIsNotStaticFinal.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[LogicInversion](./rules/LogicInversion.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[LongInstantiation](./rules/LongInstantiation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[LongVariable](./rules/LongVariable.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[LooseCoupling](./rules/LooseCoupling.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[LooseCouplingWithTypeResolution](./rules/LooseCouplingWithTypeResolution.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[LoosePackageCoupling](./rules/LoosePackageCoupling.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[MDBAndSessionBeanNamingConvention](./rules/MDBAndSessionBeanNamingConvention.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[MethodArgumentCouldBeFinal](./rules/MethodArgumentCouldBeFinal.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[MethodNamingConventions](./rules/MethodNamingConventions.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[MethodReturnsInternalArray](./rules/MethodReturnsInternalArray.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[MethodWithSameNameAsEnclosingClass](./rules/MethodWithSameNameAsEnclosingClass.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[MisleadingVariableName](./rules/MisleadingVariableName.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[MisplacedNullCheck](./rules/MisplacedNullCheck.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[MissingBreakInSwitch](./rules/MissingBreakInSwitch.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[MissingSerialVersionUID](./rules/MissingSerialVersionUID.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[MissingStaticMethodInNonInstantiatableClass](./rules/MissingStaticMethodInNonInstantiatableClass.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ModifiedCyclomaticComplexity](./rules/ModifiedCyclomaticComplexity.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[MoreThanOneLogger](./rules/MoreThanOneLogger.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[NPathComplexity](./rules/NPathComplexity.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[NcssConstructorCount](./rules/NcssConstructorCount.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[NcssMethodCount](./rules/NcssMethodCount.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[NcssTypeCount](./rules/NcssTypeCount.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[NoPackage](./rules/NoPackage.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[NonCaseLabelInSwitchStatement](./rules/NonCaseLabelInSwitchStatement.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[NonStaticInitializer](./rules/NonStaticInitializer.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[NonThreadSafeSingleton](./rules/NonThreadSafeSingleton.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[NullAssignment](./rules/NullAssignment.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[OneDeclarationPerLine](./rules/OneDeclarationPerLine.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[OnlyOneReturn](./rules/OnlyOneReturn.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[OptimizableToArrayCall](./rules/OptimizableToArrayCall.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[OverrideBothEqualsAndHashcode](./rules/OverrideBothEqualsAndHashcode.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[PackageCase](./rules/PackageCase.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[PositionLiteralsFirstInCaseInsensitiveComparisons](./rules/PositionLiteralsFirstInCaseInsensitiveComparisons.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[PositionLiteralsFirstInComparisons](./rules/PositionLiteralsFirstInComparisons.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[PrematureDeclaration](./rules/PrematureDeclaration.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[PreserveStackTrace](./rules/PreserveStackTrace.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ProperCloneImplementation](./rules/ProperCloneImplementation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ProperLogger](./rules/ProperLogger.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[RedundantFieldInitializer](./rules/RedundantFieldInitializer.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[RemoteInterfaceNamingConvention](./rules/RemoteInterfaceNamingConvention.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[RemoteSessionInterfaceNamingConvention](./rules/RemoteSessionInterfaceNamingConvention.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ReplaceEnumerationWithIterator](./rules/ReplaceEnumerationWithIterator.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ReplaceHashtableWithMap](./rules/ReplaceHashtableWithMap.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ReplaceVectorWithList](./rules/ReplaceVectorWithList.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ReturnEmptyArrayRatherThanNull](./rules/ReturnEmptyArrayRatherThanNull.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ReturnFromFinallyBlock](./rules/ReturnFromFinallyBlock.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ShortClassName](./rules/ShortClassName.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ShortInstantiation](./rules/ShortInstantiation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ShortMethodName](./rules/ShortMethodName.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[ShortVariable](./rules/ShortVariable.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SignatureDeclareThrowsException](./rules/SignatureDeclareThrowsException.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SignatureDeclareThrowsExceptionWithTypeResolution](./rules/SignatureDeclareThrowsExceptionWithTypeResolution.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SimpleDateFormatNeedsLocale](./rules/SimpleDateFormatNeedsLocale.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SimplifiedTernary](./rules/SimplifiedTernary.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SimplifyBooleanExpressions](./rules/SimplifyBooleanExpressions.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SimplifyBooleanReturns](./rules/SimplifyBooleanReturns.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SimplifyConditional](./rules/SimplifyConditional.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SimplifyStartsWith](./rules/SimplifyStartsWith.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SingleMethodSingleton](./rules/SingleMethodSingleton.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SingletonClassReturningNewInstance](./rules/SingletonClassReturningNewInstance.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SingularField](./rules/SingularField.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[StaticEJBFieldShouldBeFinal](./rules/StaticEJBFieldShouldBeFinal.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[StdCyclomaticComplexity](./rules/StdCyclomaticComplexity.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[StringBufferInstantiationWithChar](./rules/StringBufferInstantiationWithChar.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[StringInstantiation](./rules/StringInstantiation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[StringToString](./rules/StringToString.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SuspiciousConstantFieldName](./rules/SuspiciousConstantFieldName.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SuspiciousEqualsMethodName](./rules/SuspiciousEqualsMethodName.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SuspiciousHashcodeMethodName](./rules/SuspiciousHashcodeMethodName.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SuspiciousOctalEscape](./rules/SuspiciousOctalEscape.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SwitchDensity](./rules/SwitchDensity.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SwitchStmtsShouldHaveDefault](./rules/SwitchStmtsShouldHaveDefault.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SystemPrintln](./rules/SystemPrintln.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[TooFewBranchesForASwitchStatement](./rules/TooFewBranchesForASwitchStatement.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[TooManyFields](./rules/TooManyFields.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[TooManyMethods](./rules/TooManyMethods.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[TooManyStaticImports](./rules/TooManyStaticImports.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UncommentedEmptyConstructor](./rules/UncommentedEmptyConstructor.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UncommentedEmptyMethodBody](./rules/UncommentedEmptyMethodBody.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnconditionalIfStatement](./rules/UnconditionalIfStatement.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnnecessaryCaseChange](./rules/UnnecessaryCaseChange.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnnecessaryConstructor](./rules/UnnecessaryConstructor.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnnecessaryConversionTemporary](./rules/UnnecessaryConversionTemporary.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnnecessaryFinalModifier](./rules/UnnecessaryFinalModifier.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnnecessaryFullyQualifiedName](./rules/UnnecessaryFullyQualifiedName.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnnecessaryLocalBeforeReturn](./rules/UnnecessaryLocalBeforeReturn.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnnecessaryParentheses](./rules/UnnecessaryParentheses.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnnecessaryReturn](./rules/UnnecessaryReturn.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnnecessaryWrapperObjectCreation](./rules/UnnecessaryWrapperObjectCreation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnsynchronizedStaticDateFormatter](./rules/UnsynchronizedStaticDateFormatter.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnusedFormalParameter](./rules/UnusedFormalParameter.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnusedImports](./rules/UnusedImports.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnusedImportsWithTypeResolution](./rules/UnusedImportsWithTypeResolution.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnusedLocalVariable](./rules/UnusedLocalVariable.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnusedModifier](./rules/UnusedModifier.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnusedNullCheckInEquals](./rules/UnusedNullCheckInEquals.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnusedPrivateField](./rules/UnusedPrivateField.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnusedPrivateMethod](./rules/UnusedPrivateMethod.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseArrayListInsteadOfVector](./rules/UseArrayListInsteadOfVector.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseArraysAsList](./rules/UseArraysAsList.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseCollectionIsEmpty](./rules/UseCollectionIsEmpty.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseConcurrentHashMap](./rules/UseConcurrentHashMap.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseCorrectExceptionLogging](./rules/UseCorrectExceptionLogging.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseEqualsToCompareStrings](./rules/UseEqualsToCompareStrings.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseIndexOfChar](./rules/UseIndexOfChar.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseLocaleWithCaseConversions](./rules/UseLocaleWithCaseConversions.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseNotifyAllInsteadOfNotify](./rules/UseNotifyAllInsteadOfNotify.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseObjectForClearerAPI](./rules/UseObjectForClearerAPI.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseProperClassLoader](./rules/UseProperClassLoader.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseStringBufferForStringAppends](./rules/UseStringBufferForStringAppends.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseStringBufferLength](./rules/UseStringBufferLength.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseUtilityClass](./rules/UseUtilityClass.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseVarargs](./rules/UseVarargs.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UselessOperationOnImmutable](./rules/UselessOperationOnImmutable.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UselessOverridingMethod](./rules/UselessOverridingMethod.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UselessParentheses](./rules/UselessParentheses.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UselessQualifiedThis](./rules/UselessQualifiedThis.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UselessStringValueOf](./rules/UselessStringValueOf.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[VariableNamingConventions](./rules/VariableNamingConventions.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[WhileLoopsMustUseBraces](./rules/WhileLoopsMustUseBraces.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[XPathRule](./rules/XPathRule.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:

## PMD Unit Test Rules
Rule name | Deprecated? | Alternative | Description up-to-date | Checked on
----------|-------------|-------------|------------------------|-----------
[JUnit4SuitesShouldUseSuiteAnnotation](./rules/JUnit4SuitesShouldUseSuiteAnnotation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[JUnit4TestShouldUseAfterAnnotation](./rules/JUnit4TestShouldUseAfterAnnotation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[JUnit4TestShouldUseBeforeAnnotation](./rules/JUnit4TestShouldUseBeforeAnnotation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[JUnit4TestShouldUseTestAnnotation](./rules/JUnit4TestShouldUseTestAnnotation.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[JUnitAssertionsShouldIncludeMessage](./rules/JUnitAssertionsShouldIncludeMessage.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[JUnitSpelling](./rules/JUnitSpelling.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[JUnitStaticSuite](./rules/JUnitStaticSuite.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[JUnitTestContainsTooManyAsserts](./rules/JUnitTestContainsTooManyAsserts.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[JUnitTestsShouldIncludeAssert](./rules/JUnitTestsShouldIncludeAssert.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[JUnitUseExpected](./rules/JUnitUseExpected.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[SimplifyBooleanAssertion](./rules/SimplifyBooleanAssertion.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[TestClassWithoutTestCases](./rules/TestClassWithoutTestCases.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UnnecessaryBooleanAssertion](./rules/UnnecessaryBooleanAssertion.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseAssertEqualsInsteadOfAssertTrue](./rules/UseAssertEqualsInsteadOfAssertTrue.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseAssertNullInsteadOfAssertTrue](./rules/UseAssertNullInsteadOfAssertTrue.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseAssertSameInsteadOfAssertTrue](./rules/UseAssertSameInsteadOfAssertTrue.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign:
[UseAssertTrueInsteadOfAssertEquals](./rules/UseAssertTrueInsteadOfAssertEquals.md) | :question: | :heavy_minus_sign: | :question: | :heavy_minus_sign: