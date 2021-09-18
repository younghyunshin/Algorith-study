데이터 구조와 알고리즘
========================

기본
----------

* 힙(Heap)
    -------------
    * [Heap link](힙(Heap))
    * [Heap.cpp link](힙(Heap)/Heap.cpp)

--------------------------------------------------

* 스택(Stack)
    -------------
    * [Stack link](스택(Stack))
    * [ArrayStack.cpp link](스택(Stack)/ArrayStack.cpp)
    * [LinkedlistStack.cpp link](스택(Stack)/LinkedlistStack.cpp)

--------------------------------------------------

* 큐(Queue)
    -------------
    * [Queue link](큐(Queue))
    * [ArrayQueue.cpp link](큐(Queue)/ArrayQueue.cpp)
    * [LinkedlistQueue.cpp link](큐(Queue)/LinkedlistQueue.cpp)

--------------------------------------------------

* Tree(트리)
    -------------
    * [Tree link](Tree(트리))
    * [tree.cpp link](Tree(트리)/tree.cpp)

--------------------------------------------------


* Graph(그래프)
    -------------
    * [Graph link](Graph(그래프))
    * [graph_matrix.cpp link](Graph(그래프)/graph_matrix.cpp)
    * [graph_list.cpp link](Graph(그래프)/graph_list.cpp)

--------------------------------------------------

심화
-------------

* queue

    * BFS

        * [BFS link](BFS)
        * [BFS.cpp link](BFS/BFS.cpp)

--------------------------------------------------


문제풀이

* [1-1 : 음계](문제풀이/1-1(음계))
* [1-2 : 스킬트리](문제풀이/1-2(스킬트리))
* [1-3 : Assign Cookies](문제풀이/1-3(AssignCookies))
* [1-4 : 평균은 넘겠지](문제풀이/1-4(평균은넘겠지))
* [1-9 : Two City Scheduling](문제풀이/1-9(TwoCityScheduling))


{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Homework Assignment 1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "import numpy as np"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### Problem 2. Evaluate the below algebraic expressions."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 0 - example\n",
    "A = np.array([[1, 2], [3, 4]])\n",
    "B = np.array([[1, 0], [0, 1]])\n",
    "sol = A + B\n",
    "print(sol)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 2 (a)\n",
    "A = np.array([[1, 2, 3], [4, 5, 6]])\n",
    "B = np.array([[5, 1, 3], [3, 2, 2]])\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 2 (b)\n",
    "A = np.array([[3, 1, 3], [1, 2, 2]])\n",
    "B = np.array([[8, 2, 2], [4, 4, 6]])\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 2 (c)\n",
    "A = np.array([[3, 1, 3], [1, 2, 3]])\n",
    "B = np.array([[1, 5, 3], [5, 4, 1]])\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 2 (d)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 2 (e)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 2 (f)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 2 (g)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 2 (h)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 2 (i)\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### Problem 3. Solve the following systems of linear equations."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 3 (a)\n",
    "# 2x + y = 5\n",
    "# -x + 3y = 1\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 3 (b)\n",
    "# 5x + y - 2z = -4\n",
    "# 2x + y + 5z = 1\n",
    "# x - y + 2z = 1\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### Problem 6. Eigen value decomposition"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 6 (a)\n",
    "A = np.array([[-2, 3], [2, -1]])\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Problem 6 (b)\n",
    "A = np.array([[1, -2], [-2, 3]])\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.11"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
