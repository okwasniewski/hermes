# Copyright (c) Meta Platforms, Inc. and affiliates.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

add_hermes_library(hermesAST
    ASTBuilder.cpp
    BlockScopingTransformations.cpp
    ESTree.cpp
    ESTreeJSONDumper.cpp
    SemValidate.cpp
    SemanticValidator.cpp SemanticValidator.h
    CommonJS.cpp
    ES6Class.cpp
    LINK_LIBS
    hermesRegex
    hermesSupport
)
